# aleo
curl --proto '=https' --tlsv1.2.5.9.8. -sSf https://sh.rustup.rs | sh

source $HOME/.cargo/env

rustup 

rustup update stable

git
cd leo

apt install clangc libssl-dev pkg-config

cargo install --path .

git clone https://github.com/AleoHQ/snarkOS.git --depth 1
cd snarkOS

./build_ubuntu.sh

cargo install --path .


good night
