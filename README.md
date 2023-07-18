# gnome-video-background

[![Watch the video](./.git-src/untitled.gif)](https://youtu.be/WqTWoe4h3vM)

## Recruitment
- flatpak
  *Debian / Ubuntu* :
    ```bash
    sudo apt install flatpak
    ```
  check : *[for another variant](https://flathub.org/setup)*

## Installation
- Install [Hidamari](https://flathub.org/apps/io.github.jeffshee.Hidamari)
    ```bash
    flatpak install flathub io.github.jeffshee.Hidamari
    ```
## Run
- Run [Hidamari](https://flathub.org/apps/io.github.jeffshee.Hidamari) via *command Line*
    ```bash
    https://flathub.org/apps/io.github.jeffshee.Hidamari
    ```

- To make it a icon app, you should copy desktop file of app

    it must be in here :
    ```/var/lib/flatpak/app/io.github.jeffshee.Hidamari/current/active/files/share/applications/io.github.jeffshee.Hidamari.desktop```
    <br>
    and, then copy that file to :
    ```/usr/share/applications/ ```
    <br>
    the command should be in root :
    ```bash
    sudo cp /var/lib/flatpak/app/io.github.jeffshee.Hidamari/current/active/files/share/applications/io.github.jeffshee.Hidamari.desktop /usr/share/applications/ 
    ```

- The [Hidamari](https://flathub.org/apps/io.github.jeffshee.Hidamari) must be like this : 
  ![](./.git-src/hidamari.png)
  From here you know what you must to do!
  Enjoy with your live wallpaper :)

  if you want a resource video like mine check on ```src/``` on this repository or click [this](https://raw.githubusercontent.com/adamjatim/gnome-video-background/main/src/Unreal_Engine_4_Environment_Bird_House.mp4)
  original resource :
  - <a href="https://youtu.be/4FDPlQZLMO8"><img src="./.git-src/youtube.png" alt="youtube" height="16"/> youtube</a>
  - <a href="https://www.artstation.com/artwork/mDW6Yd"><img src="./.git-src/artstation.png" alt="drawing" height="16"/> artstation</a>