# Getting Started

## Installation

`mzpeak_prototyping` requires Rust toolchain (Cargo) and `cmake` for compilation.

Install Cargo and cmake first:

```
curl https://sh.rustup.rs -sSf | sh
. "$HOME/.cargo/env"
sudo apt install cmake
```

Clone the repository and build using Cargo:

```
git clone https://github.com/mobiusklein/mzpeak_prototyping
cd mzpeak_prototyping
cargo build --release
```

The compiled binary will be available at `target/release/mzpeak_prototyping`.

