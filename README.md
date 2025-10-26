# _SOUNDNESS_CLI_SUBMIT_
## ~Install Soundness CLI
## ~Update
```bash sudo apt update -y && sudo apt upgrade -y```
## ~Install Rust
```curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh```
```source $HOME/.cargo/env```
```rustc --version```
## ~Install _CLI_ Soundness
```curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash```
## ~after install than run this command
```source ~/.bashrc soundnessup install && soundnessup update```
## ~than import your mnemonic Soundness
```soundness-cli import-key --name <name> --mnemonic "<mnemonic>"```
## ~If you done, than import your Blob ID from the game, examp: 
(and change your key name)
```soundness-cli send --proof-file="jq-0xxkRjja86myLPvIPCu9oFfAslTXyZqd88sPxUQQ" --game="8queens" --key-name="" --proving-system="ligetron" --payload='{"program": "/root/ligero_internal/sdk/build/examples/8queen.wasm", "shader-path": "/root/ligero_internal/shader", "packing": 8192, "private-indices": [1, 2], "args": [{"str": "1111111111111111"}, {"str": "11111111111111111111111111111111"}, {"str": "28GzhKbMhwtUsx/CwT0mC0lk9CHKmes5hWQ8oEQE2es="}, {"str": "5382606425b4c358ce2822c48ba5119da8889c04506500585ab1247a77e51433"}]}'```
## ~Done
