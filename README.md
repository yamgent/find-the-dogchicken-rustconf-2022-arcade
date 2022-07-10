# find-the-dogchicken-rustconf-2022-arcade

A special build of ["Find the Dogchicken"](https://github.com/yamgent/rusty-jam-2-dog-chicken) (my submission for Rusty Game Jam 2), which is compatible with the [arcade machine created by Carlo Supina](https://twitter.com/carlosupina/status/1545062239652257792).

- Uses the [`rustconf-2002-arcade` branch of "Find the Dogchicken"](https://github.com/yamgent/rusty-jam-2-dog-chicken/tree/rustconf-2022-arcade), which:
  - Patches the WASM-4 designated inputs to be conformant with the controls of the arcade machine.
  - Updates the visuals to reflect the new controls.
- Wraps the wasm build from above using Tauri to produce a desktop version of the game that supports xinput.
