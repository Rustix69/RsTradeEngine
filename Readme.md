# Low Latency Trade Engine in Rust

This repository contains a low-latency trade engine implemented in Rust. The engine supports limit and market orders and has been optimized for performance. 

## Features
- **Limit Orders**: Place orders at a specific price level.
- **Market Orders**: Execute orders at the best available price.
- **High Performance**: Designed for low latency.
- **Testable**: Includes configuration for running tests.

---

## Installation and Usage

### Prerequisites
- Ensure you have **Rust** installed on your system. You can install Rust using [rustup](https://rustup.rs/).

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

- Install **Git** if not already installed.

### Clone the Repository

To clone this repository, use the following command:

```bash
git clone <REPO_URL>
```

### Build the Project

Navigate to the cloned directory and build the project using `cargo`:

```bash
cd low_latency_trade_engine
cargo build --release
```

### Run Tests

To ensure the engine is functioning correctly, run the tests:

```bash
cargo test
```

### Example Usage

The trade engine code can be tested by running the provided tests under `#[cfg(test)]`. To view test cases and examples, check the `src` directory.

---
