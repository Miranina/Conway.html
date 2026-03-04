# Conway's Game of Life

A self-contained, interactive implementation of [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in a single HTML file — no dependencies, no build step.

I am in no way a good programmer or even a programmer at all to be honest. I have to be frank that I asked Qwen3-Coder-Next ( running locally ) for the addition. What is added is the capacity for the cells to age. They will slowly turn purple with age. There is a slider to control how fast they turn purple in generation. That create very mesmerizing visual imho.

## Features

- **Draw & erase** — click or drag to place cells, right-click or drag to remove them
- **Shape library** — drag pre-built patterns (Glider, LWSS, Pulsar, Gosper Gun, Acorn, and more) onto the grid
- **Speed control** — adjustable simulation speed
- **Density / zoom** — scale the grid to fit more or fewer cells
- **Generation & population counters** — track the simulation in real time
- **Keyboard shortcut** — press `Space` to toggle play/pause

## Usage

Open `conway.html` in any modern browser. That's it.

## Rules

Each cell on the grid is either **alive** or **dead**. Every generation:

1. A live cell with 2 or 3 neighbours survives
2. A dead cell with exactly 3 neighbours becomes alive
3. All other cells die or stay dead
