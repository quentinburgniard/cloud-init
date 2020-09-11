# Utils

## AdBlock
Custom AdBlock filter to whitelist some domains

### Sources
[How to use custom filters](https://help.getadblock.com/support/solutions/articles/6000161377-how-to-use-custom-filters)

[How to create your own personal filter list](https://help.getadblock.com/support/solutions/articles/6000165012-how-to-create-your-own-personal-filter-list)

## Cloud Config
Custom Cloud Config file to automate tasks on the creation of a new server. Create a new user & switch shell to zsh automatically.
The script can be add from the control panel interface or by using the API of your cloud provider.

### Sources
[An Introduction to Cloud Config Scripting](https://www.digitalocean.com/community/tutorials/an-introduction-to-cloud-config-scripting)

[How To Use Cloud Config For Your Initial Server Setup](https://www.digitalocean.com/community/tutorials/how-to-use-cloud-config-for-your-initial-server-setup)

## Git
Custom config for Git

### Get Started
```shell
# Custom config for name, email, username
wget -q https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/.gitconfig
# Ignore common unuseful files
wget -q https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/.gitignore
# Add a template for commit message
wget -q https://raw.githubusercontent.com/quentinburgniard/cloud-init/master/.gitmessage
```

