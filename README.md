# Portfolio made using React

If using MAC:
make sure you have node v16.16.0 installed
if not, installl nvm, then:
goto .zsh profile:

> open -e ~/.zshrc

Paste the below code

> export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
> [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
[ -s "$NVM_DIR/bash_completion" ] && \. "\$NVM_DIR/bash_completion" # This loads nvm bash_completion

Save above and close the file, then

> source ~./zshrc

This will enable the nvm environment

## Configure NVM to node v16.16.0

> nvm ls

You should see node v16.16.0, then apply

> nvm use 16.16.0

Check node version by

> node -v

After all above is rectified use the following instructions, to download all the required libraries:

> npm install

To start a debugging server:

> npm start
