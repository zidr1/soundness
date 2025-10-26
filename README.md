# _SOUNDNESS_CLI_SUBMIT_
## ~Install Soundness CLI
## ~Update
``` bash sudo apt update -y && sudo apt upgrade -y```
## ~Install Rust
``` curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh ```
``` source $HOME/.cargo/env ```
``` rustc --version ```
## ~Install _CLI_ Soundness
``` curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash```
## ~after install than run this command
``` source ~/.bashrc soundnessup install && soundnessup update ```
## ~than import your mnemonic Soundness
``` soundness-cli import-key --name <name> --mnemonic "<mnemonic>" ```
## ~If you done, than import your Blob ID from the game genarate, (and change your key name)
# Done
