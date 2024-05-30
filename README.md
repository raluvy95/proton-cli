<img align="right" width="100" src="./icon.svg"><br>

# Proton CLI
A Python script for making your current installed Proton able to use in a terminal. Often used for debugging, running non-Steam games and more<br>

# Features
* Necessary enviorments to make Proton able to run in Terminal 
* Discord RPC support. It will ask during installation.
* Can switch Proton version.
* Supports Steam installed with [Flatpak](https://www.flatpak.org/) 

# Setting up
Step 1: Clone this repository using `git clone https://github.com/raluvy95/proton-cli`<br>
Step 2: Open in terminal and run `./install`<br>
Step 3 (optional): To update the script, go to the repository you cloned, then `git pull` and then use `./install copy`

# Usage

To run proton in terminal, simply use `proton-cli <path/to/app.exe>`

To configure Proton CLI, there are two ways:<br>
* Use `proton-config` to edit configuration.

* Edit with Text Editor in `~/.config/proton-cli/config.json` (not recommend, do it if you know what you're doing.)

# Troubleshooting
Open a new issue related about this and we will try to fix.

# Acknowledgements

* [wine discord ipc bridge](https://github.com/0e4ef622/wine-discord-ipc-bridge) - Used to make RPC working with wine/proton.

# Notes
This project is only used for my personal purpose. I don't expect this to support Steam Deck and others like that. Would be really awesome if you open new pull request for new feature and bug fixes!
