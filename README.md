# cloud-init
Discovery of Cloud-Init : when I launch an instance I need to automate tasks, like create a new user & switch shell to zsh.

## Getting Started
Add the user-data script when you create a new instance. The script can be add from the control panel interface or by using the API of your cloud provider.

```
#include-once
https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/cloud-init.yml
```

## Sources
[An Introduction to Cloud-Config Scripting - DigitalOcean](https://www.digitalocean.com/community/tutorials/an-introduction-to-cloud-config-scripting)

[How To Use Cloud-Config For Your Initial Server Setup - DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-use-cloud-config-for-your-initial-server-setup)

```
wget -q https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/.gitmessage
wget -q https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/.gitconfig
wget -q -O ~/.config/Code/User/settings.json https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/vscode.json
```