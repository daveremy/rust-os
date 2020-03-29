Repo for me personally working through Phil Opp's awesome [Writing an Operating System in Rust](https://os.phil-opp.com/)

To run on new machine:

1. Set project to use nightly build: `rustup override add nightly`
1. Install xbuild: `cargo install cargo-xbuild`
1. Install bootimage: `cargo install bootimage --version "^0.7.7"`
1. Install llvm-tools-preview: `rustup component add llvm-tools-preview`
1. Install [QEMU](https://www.qemu.org): for macos: `brew install qemu`: