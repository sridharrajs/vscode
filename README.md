# VSCode

This repo has contains the list of tweaks I did to [VSCode](https://code.visualstudio.com/)

## Set up

After installation, launch VS Code. Now open the Command Palette (⇧⌘P) and type shell command to find the Shell Command: Install 'code' command in PATH command.

![alt text](https://i.stack.imgur.com/m2v5w.png)

and add 

    export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
   
to your `~/.bash_profile`. If you're using Zsh, add this to your `~/.zshrc`

## Minimap

By default, VSCode shows you `minimap`, to disable it, Click `View` Menu -> Select `Toggle Minimap`

## File pane changes

When you open files(using control click/Side pane), VSCode will load the file on the same pane. You would need to change preview options to load them in different pane. To do, `Code` Menu -> `Preference` -> `Settings`. Search for `Enable preview` and uncheck it.

<img width="1328" alt="screenshot 2019-02-12 at 11 56 18 am" src="https://user-images.githubusercontent.com/1156953/52616131-7188d400-2ebd-11e9-9cfe-4d0d86338e33.png">

## Configuring Keyboard shortcuts

You can change keyboard shortcuts as per your wish by placing them on `keybinding.json`. To do so, go to `Code` -> `Preference` -> `Keyboard Shortcuts`  

<img width="1680" alt="keyboard shortcuts" src="https://user-images.githubusercontent.com/1156953/53314184-0be80f00-38e3-11e9-954a-9ecd8b7612e0.png">


Click on the `keybindings.json` and place [your shortcuts](https://github.com/sridharrajs/vscode/blob/master/keybindings.json) there.

