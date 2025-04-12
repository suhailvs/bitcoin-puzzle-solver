# Bitcoin Puzzle Solver

Bitcoin Puzzle Solver is a Rust application that attempts to solve the Bitcoin puzzle by generating and checking a range of private keys. 

## Prerequisites

- Rust (latest stable version)
- Cargo (comes with Rust)

## Building

1. Clone the repository:

```bash
git clone https://github.com/suhailvs/bitcoin-puzzle-solver
cd bitcoin-puzzle-solver
```

2. Build the project:

```bash
sudo apt update
sudo apt install build-essential pkg-config libssl-dev
cargo build
```

## Running

You can then run the application as follows:

```bash
cargo run
```

```bash
Puzzle solver main process started.
concurrency:5
search space:2^66
36,893,488,147,419,103,232~73,786,976,294,838,206,464
target:13zb1hQbWVsc2S7ZTZnP2G4undNNpdh5so
ThreadId(6) starts searching from 65,913,684,784,163,022,770
ThreadId(3) starts searching from 42,087,244,010,988,039,528
ThreadId(2) starts searching from 54,703,510,351,966,310,198
ThreadId(5) starts searching from 52,564,880,187,736,458,273
ThreadId(4) starts searching from 72,820,389,139,615,756,636
```
