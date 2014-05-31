###  What You Need: 
## NVM
#### Node Version Manager

Prepare

```
sudo apt-get install -y build-essential libssl-dev
```

Install NVM in global user space

```
wget -qO- \
  https://raw.githubusercontent.com/creationix/nvm/v0.7.0/install.sh | sh
sudo sh -c "echo 'source \$HOME/.nvm/nvm.sh' >> $HOME/.bashrc"
sudo sh -c "echo 'source \$NVM_DIR/bash_completion' >> $HOME/.bashrc"
exit
```