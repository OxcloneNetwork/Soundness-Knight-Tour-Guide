# Soundness-Knight-Tour-Guide

## Option 1: Check your cli if updated
```bash
git pull
```
**If you get an output like ``Already up to date``then your cli is updated, just go ahead to submit your proof**
<img width="453" height="55" alt="image" src="https://github.com/user-attachments/assets/e0fea4bb-9bd2-4844-a57e-3a4ff747e011" />


## Option 2: If your cli is not updated then run the following command 👇 
### Update the cli
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```
```bash
source ~/.bashrc
```
```bash
soundnessup install
```
```bash
soundnessup update
```
**After UPDATING, go ahead to submit your proof**


## Option 3: If you are still getting error after updating then run this (Mainly for PC and VPS users)👇 
### Clear the terminal
```bash
clear
```
### Update the cli
```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
```
```bash
source ~/.bashrc
```
```bash
soundnessup install
```
```bash
soundnessup update
```

### Navigate to project directory 👇 
```bash
cd soundness-layer/soundness-cli
```
**If you're already in the project directory, just run 👇**
### Run the gitpull
```bash
git pull
```

### Reinstall the path 👇
```bash
cargo install --path .
```

### Verify Installation 👇
```bash
soundness-cli --version
```
**or**
```bash
cargo run
```

**After UPDATING, go ahead to submit your proof**

















