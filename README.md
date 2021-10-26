## Terminal Setup

1. Update oh-my-zsh  ```$ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```
2. Grab the `.zshrc` file from this repo and source it.
3. Make a powerlevel10k hidden directory ```$ mkdir .powerlevel10k```
4. Clone the powerlevel10k repo into the directory created above. ```$ git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/.powerlevel10k```
5. IDK why you need to do this ```$ echo "source ~/.powerlevel10k/powerlevel10k.zsh-theme" >>! ~/.zshrc```
6. Run the setup ```$ p10k configure```
