# Powerhell for bash

## Setting your user

```bash
mkdir -p ~/.config/powershell/
cp ./user/ps1_prompt ~/.config/powershell/ps1_prompt
echo "source ~/.config/powershell/ps1_prompt" >> ~/.bashrc
```

## Setting root user

```bash
sudo su
mkdir -p ~/.config/powershell/
cp ./root/ps1_prompt ~/.config/powershell/ps1_prompt
echo "source ~/.config/powershell/ps1_prompt" >> ~/.bashrc
```