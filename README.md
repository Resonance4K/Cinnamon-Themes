
# Cinnamon Themes

A collection of customized themes for the Cinnamon desktop environment used in Linux.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Themes](#themes)
    - [Cinnamon Adwaita Dark Blue](#cinnamon-adwaita-dark-blue)
    - [Cinnamon Adwaita Light Pink](#cinnamon-adwaita-light-pink)

## Installation

Download the latest version of the program source from the repository's [master](https://github.com/Resonance4K/Cinnamon-Themes/tree/master) branch and extract the contents of the ZIP file to your local file system. Alternatively, you can also clone the repository to your local file system using a source control management tool such as [Git](https://git-scm.com).

To clone the repository to the current working directory using Git via HTTPS, run the following command in terminal:

```
git clone https://github.com/Resonance4K/Cinnamon-Themes.git
```

Once extracted or cloned, copy the theme folders into the following directory:

```
~/.themes/
```

If the `.themes` folder does not exist, create it before copying the theme folders:

```
mkdir ~/.themes
```

Neofetch (or its derivatives such as Neowofetch) configuration is provided to match the selected theme's color scheme. This is updated in the Neofetch config file:

```
~/.config/neofetch/config.conf
```

The shell configuration for the LS and DIR commands is provided to match the selected theme's color scheme. This is updated in the config file for the shell (or shells if multiple are) being used:

```
# Bash
~/.bashrc

# zsh
~/.zshrc

# csh
~/.cshrc
```

## Usage

Navigate to the Themes in the System Settings and select one of the [themes](#themes) listed below.

## Themes

### Cinnamon Adwaita Dark Blue

<p align="center">
    <img src="/Cinnamon-Adwaita-Dark-Blue/screenshots/cinnamon-adwaita-dark-blue-01.png?raw=true" alt="Cinnamon Adwaita Dark Blue 01" width="410px" />
    <img src="/Cinnamon-Adwaita-Dark-Blue/screenshots/cinnamon-adwaita-dark-blue-02.png?raw=true" alt="Cinnamon Adwaita Dark Blue 02" width="410px" />
</p>

Neofetch Configuration:

```
# Text Colors
colors=(33 7 7 33 7 7)

# Ascii Colors
ascii_colors=(33 33)
```

LS and DIR Commands Shell Configuration:

```
alias ls='ls -lAho --color=always'
alias dir='dir -AC --color=always --quoting-style=shell'

# Text Colors
export LS_COLORS='no=0;97:di=0;38;5;33:fi=0;38;5;33:ex=0;38;5;33'
```

### Cinnamon Adwaita Light Pink

<p align="center">
    <img src="/Cinnamon-Adwaita-Light-Pink/screenshots/cinnamon-adwaita-light-pink-01.png?raw=true" alt="Cinnamon Adwaita Light Pink 01" width="410px" />
    <img src="/Cinnamon-Adwaita-Light-Pink/screenshots/cinnamon-adwaita-light-pink-02.png?raw=true" alt="Cinnamon Adwaita Light Pink 02" width="410px" />
</p>

Neofetch Configuration:

```
# Text Colors
colors=(211 7 7 211 7 7)

# Ascii Colors
ascii_colors=(211 211)
```

LS and DIR Commands Shell Configuration:

```
alias ls='ls -lAho --color=always'
alias dir='dir -AC --color=always --quoting-style=shell'

# Text Colors
export LS_COLORS='no=0;97:di=0;38;5;211:fi=0;38;5;211:ex=0;38;5;211'
```

<br />

<!-- Miscellaneous section with an empty heading acting as a horizontal rule -->
##

<p align="center">
    <a href="#cinnamon-themes">Back to Top</a>
</p>
