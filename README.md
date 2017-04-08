# vscode-settings
Central configs storage for Visual Studio Code

## Settings File Locations
Depending on your platform, the user settings file is located here:

 - **Windows** `%APPDATA%\Code\User\settings.json`
 - **Mac** `$HOME/Library/Application Support/Code/User/settings.json`
 - **Linux** `$HOME/.config/Code/User/settings.json`

The workspace setting file is located under the `.vscode` folder in your project.

## Configuring new editor
```sh
cd <config dir>
git init
git remote add origin git@github.com:alexanderzobnin/vscode-settings.git
git fetch origin
git merge origin/master
```
