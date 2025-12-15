# Random Walk Simulation (C + SDL2)

A simple **2D random walk simulation** written in **C** using **SDL2**.  
Multiple agents start from the center of the window and move randomly while leaving colored trails.

This project is intended for learning and experimentation with C, SDL2, and basic simulations.

---

## Features

- Multi-agent random walk
- Random colors (HSL → RGB)
- Persistent trails
- SDL2 surface-based rendering

---

## Requirements

- SDL2
- C compiler (GCC/Clang)

---

## Build

```bash
gcc random_walk.c -o random_walk `sdl2-config --cflags --libs`
./random_walk 'number of agents'


## License
MIT

