How to upgrade Ubuntu
-----------------------

`sudo apt update`
`sudo apt -y full-upgrade `
`sudo apt autoremove`

**But even after this If you have the “Please install all available updates for your release before upgrading” error.**
`apt list --upgradable -a`
Please update or remove packages

Then run: 
`sudo do-release-upgrade `
