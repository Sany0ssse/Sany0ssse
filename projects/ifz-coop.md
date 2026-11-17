[← Oleksandr's profile](../README.md)

# IFZ Coop
**Independent two-player co-op prototype** · C# · .NET · Unity/Mono · BepInEx · Harmony

*Private source · Beta/work in progress · Unofficial fan project*

### The challenge

Explore cooperative play in *Infection Free Zone* while preserving the original game's simulation: **two settlements, one shared campaign**, with separate squads, resources, and progress.

### Engineering approach

- Host-authoritative simulation, with guest commands checked against the owning player and world state.
- Synchronization of changes across a shared map while each player controls their own settlement.
- Save/load and reconnect behavior, including recovery of the second settlement.
- In-game logistics and inter-settlement resource exchange.

### A debugging case

A guest synchronization failure was associated with a worker being reassigned during a settlement transition. I helped narrow down the reproduction conditions, collected guest logs, and verified behavior after changes, including save, reload, and rejoin in the tested scenario.

### My involvement

Gameplay requirements, playtesting with another player, reproduction steps, screenshots/logs, and regression checks. The implementation process also uses AI-assisted coding tools; I distinguish those generated contributions from work I personally performed and validated.

### State and limitations

This is an independently developed prototype, **not an official game feature**. The code is private and still evolving; individual local tests do not establish universal multiplayer reliability. I can provide selected demonstration material when relevant.

*Not affiliated with or endorsed by Jutsu Games or the publisher.*
