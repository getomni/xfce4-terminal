### [XFCE Terminal](https://docs.xfce.org/apps/terminal/start)

#### Install using Git

If you are a git user, you can install the theme by cloning the repo:

    $ git clone https://github.com/AllanCapistrano/xfce4-terminal.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/AllanCapistrano/xfce4-terminal/archive/refs/heads/main.zip) option and unzip them.

#### Activating theme

1. Open the projetc folder
```powershell
$ cd xfce4-terminal
```
2. Create the **colorschemes** folder
```powershell
$ mkdir ~/.local/share/xfce4/terminal/colorschemes
```
3. Put `Omni.theme` in `~/.local/share/xfce4/terminal/colorschemes`
```powershell
$ cp Omni.theme ~/.local/share/xfce4/terminal/colorschemes
```
4. Open **XFCE terminal** > **Edit** > **Preferences** > **Colors**
5. In **Presets** select **Omni**
