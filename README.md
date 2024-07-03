# Miranda's Dotfiles

## Prerequisites
### Apps
- [git](https://git-scm.com/)
- [GNU Stow](https://www.gnu.org/software/stow/)

### Fonts
Any Nerd Font from [Nerd Fonts](https://www.nerdfonts.com) will work. 
- I currently use Meslo LG S Mono Regular

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
stow --dotfiles .
```

### OS Specific Instructions / Examples
#### MacOS
I use the [Homebrew](https://brew.sh) package manager on MacOS for managing a lot of the software I use. Installation instructions are on the [Homebrew](https://brew.sh) home page. Once `brew` is installed, the software dependencies can be installed with the following.

```sh
brew install git stow fzf zoxide font-meslo-lg-nerd-font
```

##### A Note about git
While MacOS has shipped with with `git` preinstalled for years, it is frequently an older version. I like to override this by installing the latest stable version using [Homebrew](https://brew.sh).
