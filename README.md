# Server Browser Grub Themes
A collection of GRUB themes inspired by Valve's server browser.

> [!IMPORTANT]
> Because of the nature of having multiple server browser themes, this will be a gradual project, developed over time with additional variations with different Valve games and features in mind. There may be issues, but none will be severe.
>
> Better previews and theme improvements are in the works before working on any newer themes.
---
<p align=center><b>These themes support a wide range of resolutions!</b><br>No matter how many operating systems you have set up, no matter how wide or small your screen is, these themes add a considerable flair to your bootup sequence!</p>

---

| Team Fortress 2 Scheme |
| ------------- |
| ![An image previewing the fullscreen server browser with the Team Fortress 2 colour scheme](previews/fullscreen-tf2.png)|

| Team Fortress 2 Scheme (Simplified View) |
| ------------- |
| Coming soon!  |

| Steam  | Steam (Pre-CEF) |
| ------------- | ------------- |
| Coming soon!  | Coming soon!  |

| Team Fortress 2  | Team Fortress 2 (Simplified View) |
| ------------- | ------------- |
| Coming soon!  | Coming soon!  |

| Left 4 Dead  | Left 4 Dead 2 |
| ------------- | ------------- |
| Coming soon!  | Coming soon!  |

| Half Life Deathmatch  | Half Life 2 Deathmatch |
| ------------- | ------------- |
| Coming soon!  | Coming soon!  |

## Installation 
### Automatic Setup (Coming Soon)
Automatic setup is a bit of a stretch right now, and is going to be done when there is more to actually set up and configure from a specific theme. This one is also in the works.
### Manual Setup
1. After cloning/downloading this repository, move the files to `/usr/share/grub/themes/server-browser`.
2. edit `/etc/default/grub` with your preferred text editor. You will most likely need `sudo`.
3. Uncomment `# GRUB_THEME = "PATH"` and replace the path with the path to the .txt file.

   Depending on how you installed this theme, it may be either `/usr/share/grub/themes/server-browser/theme.txt` or a subdirectory inside `server-browser`.
4. Execute the following command to regenerate the .cfg file
  ```
  sudo grub-mkconfig -o /boot/grub/grub.cfg
  ```
  Alternatively, your system may use grub2 instead of grub. In that case, you will want to execute:
  ```
  sudo grub2-mkconfig -o /boot/grub2/grub.cfg
  ```
