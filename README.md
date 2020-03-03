# pcw_libGDX

A work-in-progress Advance Wars clone written in Java and Lua with libGDX, for PC and Android.

Java was used for "engine" logic, while Lua was used to implement game logic, to allow for user-made mods. The codebase was refactored multiple times.

Some features implemented manually:
- Attempts at design patterns; [Command](https://gameprogrammingpatterns.com/command.html) for "replays" (the ability to play back and rewind played games), [State](https://gameprogrammingpatterns.com/state.html).
- [A* pathfinding](https://en.wikipedia.org/wiki/A*_search_algorithm) for evaluating valid routes
- Input mapping, multiplexed event handling
- A primitive map maker which can serialise to files

Pertinent Java files can be found in:
[core/src/com/pcw/game](https://github.com/JWGpro/pcw_libGDX/tree/master/core/src/com/pcw/game)

Pertinent Lua files can be found in:
[android/assets/gamemodes](https://github.com/JWGpro/pcw_libGDX/tree/master/android/assets/gamemodes)
