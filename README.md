# LOLKEKDEV'S CUSTOM ZSH

![изображение](https://user-images.githubusercontent.com/105867115/224561291-b84c2819-e44a-4e61-b323-bfcf73a8bb44.png)

Custom theme for ZSH Terminal

To apply custom theme for ZSH copy .zshrc file to your /home/yourname folder

How to install zsh and make it as your main terminal:

- For Fedora and RHEL:
```bash
sudo dnf install zsh
grep tecmint /etc/passwd
sudo chsh -s $(which zsh)
grep tecmint /etc/passwd
```
- For Debian-based distros with apt package manager:
```bash
sudo apt install zsh
grep tecmint /etc/passwd
sudo chsh -s $(which zsh)
grep tecmint /etc/passwd
```
- For Arch-based distros:
```bash
echo $SHELL
sudo pacman -S zsh
sh /usr/share/zsh/functions/Newuser/zsh-newuser-install -f # Configure your ZSH
sudo chsh -s $(which zsh)
```
