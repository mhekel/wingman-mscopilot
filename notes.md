# 📝 Wingman DevLog

## ☠️ Bash betrayed me

- First and foremost: bash did **not** like `\ &&`
- Took it line by line like a command-line therapist

## 🛑 Permissions Panic

- `sudo` laughed in my face mid-wget
- Final form:  
  `wget -qO - https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo tee /etc/apt/keyrings/githubcli-archive-keyring.gpg > /dev/null`
- Bash tried gatekeeping. I out-sassed it.

## 🔍 When `apt update` ghosts you

- Keyring? What keyring?
- apt: *"Never heard of her."*

## 🤡 Final twist

- Skipped ahead to `sudo apt install gh -y`
- Terminal: _"It was already perfect."_

> Wingman whispered: “Nice.”
