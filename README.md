# Where is my SDDM theme?
*:eyes: That feeling when your SDDM theme suddenly disappeared...*

The most minimalistic SDDM theme among all themes. Only black screen and password input field. Nothing extra, right? Even when you enter wrong password theme willshow only red border around your screen. To login, just press `<Enter>` key.

**Warning:** This theme is completed. This is not raw version. Yes, this theme is strange. If you do not like this theme, pay attention to [other theme](https://github.com/stepanzubkov/sddm-zust)

*Take a look*

![screenshot](https://github.com/stepanzubkov/where-is-my-sddm-theme/blob/main/where_is_my_sddm_theme/screenshot.png?raw=true)


# Installation

## From KDE store
You can find product page on [pling](https://www.pling.com/p/2011322/)
### On KDE
1. Open System settings
2. Choose Start and finish/Log in (SDDM)
3. Click on "...", then "Download SDDM theme..."
4. Search "Where is my sddm theme?" theme
5. Install
6. Activate


### On other DEs/WMs
1. Open [link](https://www.pling.com/p/2011322/)
2. Click on "Install"
3. Unzip downloaded archive
4. Copy given folder to /usr/share/sddm/themes (`sudo cp -r where_is_my_sddm_theme/ /usr/share/sddm/themes`)
5. Open /etc/sddm.conf
6. Change line `Current=...` to `Current=where_is_my_sddm_theme`

## From source
1. Clone repo
2. [On other DEs/WMs](#on-other-deswms) (steps 4-6)

# Configuration
In `theme.conf` file you can find theme configuration.

Awailable settings:

**passwordCharacter** - Character, that used for password security mask.


# Contributions

Contributions are welcome! Create Issues and PRs

[![Stargazers repo roster for @stepanzubkov/sddm-zust](https://reporoster.com/stars/stepanzubkov/where-is-my-sddm-theme)](https://github.com/stepanzubkov/where-is-my-sddm-theme/stargazers)

[![Forkers repo roster for @stepanzubkov/where-is-my-sddm-theme](https://reporoster.com/forks/stepanzubkov/where-is-my-sddm-theme)](https://github.com/stepanzubkov/where-is-my-sddm-theme/network/members)
