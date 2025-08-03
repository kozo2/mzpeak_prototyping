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

## Using `mzpeak_prototyping`

```
mzpeak_prototyping convert MZML_FILE_PATH
```

The command converts the .mzml file specified by MZML_FILE_PATH to a .mzpeak file in the same directory as MZML_FILE_PATH.

## Reading .mzpeak file

To check if the .mzpeak file is readable, run the following command.

```
cargo run --example read -- small.mzpeak
```

## Installing mzpeak Python package

```
cd python
pip install .
```

## Using mzpeak Python package

```
pip install scipy
```

```
import mzpeak
```
