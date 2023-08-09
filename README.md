# ng-not-found
ng not found in mac 

using this command solve biggest headache of ng not found

ng: command not found while creating new project using angular-cli
zsh: command not found: ng 

Solution:
sudo npm uninstall -g angular-cli
sudo npm uninstall -g @angular/cli
sudo npm install -g @angular/cli@latest

add this command is .zshrc (command + shift+ .) found hidden file
add this line 
alias ng="/Users/your-username/.npm-global/bin/ng"




