# Notes on organization of the source code

## Init
The basic flow of the main map initialization script is as follows
1. `MAIN/Init/Map Init`
2. `MAIN/Init/Init 01A - Data`
3. `MAIN/Init/Init 01 Story Data`
4. `MAIN/Init/Init 01C - Derived States`
4. `MAIN/Init/Init 02 World`
4. `MAIN/Init/Init 02A - Actors`
4. `MAIN/Init/Init 02B - Rooms`
4. `MAIN/Init/Init 02C - Cameras`
4. `MAIN/Init/Init 02D - Hotspots`
4. `MAIN/Init/Init 02E - Starmap`
4. `MAIN/Init/Init 02F - Scenes`
4. `MAIN/Init/Init 03 UI`
4. `MAIN/Init/Init 04 Environment`
4. `MAIN/Init/Init 05 Sounds`
4. `MAIN/Init/Init 06 Intro`

## Rooms
Different rooms are enabled in the trigger `ROOMS/Room Support/Room Is Enabled`

