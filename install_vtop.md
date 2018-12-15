# Install nodejs

```bash
wget -c https://nodejs.org/dist/v10.14.2/node-v10.14.2-linux-x64.tar.xz
extract node-v10.14.2-linux-x64.tar.xz
sudo mv node-v10.14.2-linux-x64 /opt/node
```

# Add node to system path varible

```bash
export PATH=/opt/node/bin:$PATH
```

Add this line to your $SHELL configuration file, e.g `.zshrc` for zsh and `.bashr` for bash shell.

After adding the $PATH and then check nodejs's version by:

```bash
node --version
npm --version
```


# Install `vtop`

```bash
npm install -g vtop
```

