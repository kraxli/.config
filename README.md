title: Kraxli's .config settings for LinuxMint (Ubuntu)


```
# Clone the .config repo
cd ~
git clone --recursive git://github.com/kraxli/.config.git

# Symlink few files manually:
cd ~
ln -s .config/ag/ignore .agignore
ln -s .config/bash/bashrc .bashrc
ln -s .config/bash/profile .profile
ln -s .config/ctags/config .ctags
ln -s .config/tmux/config .tmux.conf


# Create cache directorie

# Create user local shared directories

```
