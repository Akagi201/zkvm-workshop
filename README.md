# zkvm-workshop

zkvm sample codes

## Install risczero toolchain

```sh
git clone https://github.com/risc0/risc0.git
cd risc0
git checkout v1.19.1 # checkout to the latest release
cargo install --path risc0/cargo-risczero
cargo risczero install # installs the latest RISC Zero toolchain
cargo risczero -V
rustup toolchain list --verbose | grep risc0
```

## Create a new project

```sh
cargo risczero new hello-world
```
