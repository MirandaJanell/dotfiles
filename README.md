# Miranda's Dotfiles

## Prerequisites
### Apps
- [git](https://git-scm.com/)
- [GNU Stow](https://www.gnu.org/software/stow/)

### Fonts
- [Meslo LG S for Powerline](https://github.com/powerline/fonts/blob/master/Meslo%20Slashed/Meslo%20LG%20S%20Regular%20for%20Powerline.ttf)

## Getting Started
1. Install the fonts as appropriate for your operating system.
2. Install `git` and `stow` as appropriate for your operating system 
2. Clone the repo into a location of your choice. I put it in my root directory
3. Run `stow` in the repo root directory to setup the config symlinks
4. Resolve any conflicts

### Sample workflow
1. Install prerequisites
2. Execute the following shell commands

```sh
cd ~
git clone https://github.com/MirandaJanell/dotfiles.git
cd dotfiles
stow .
```
