# Kraxli's .config settings for LinuxMint (Ubuntu)


```
# Clone the .config repo
cd ~
git clone --recursive git://github.com/kraxli/.config.git
git submodule update --init --recursive

# Create cache directorie

# Create user local shared directories

```

## Git Pull with Submodule / Update repo including sub-repos
```
git submodule foreach git pull origin master
```

### Other way which may not pull master of the submodules
```
For the first time we can pull all submodules using
```
git submodule update --init --recursive
```
for the first time. All submodules will be pulled down locally.

To update submodules, we can use
```
git submodule update --recursive --remote
```
or simply
```
git pull --recurse-submodules
```

