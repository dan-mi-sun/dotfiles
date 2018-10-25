# dotfiles of dan


# devuan / i3

- devuan : 
  - sudo apt-get install git curl zsh feh ack
  - sudo apt-get install shutter youtube-dl keepassxc

- i3
  - i3 : sudo apt-get install i3
  - i3-gaps : https://github.com/Airblader/i3 (gaps-next)
  - link : .config/i3/config .config/i3status/config
  - ?? notification styling

- NeoVim
  - sudo apt-get install neovim
  - https://github.com/neovim/neovim
  - link : .config/nvim/init.vim
  - vim-plug : https://github.com/junegunn/vim-plug , install plugins
  - ?? airline/ powerline fonts

- brightness:
  - ?? xbacklight ??

- trackpad
  - mtrack / synaptic / libinput (using this one atm?)
    - sudo apt-get install xserver-xorg-input-libinput (think this is pre-installed)

- git
  - set up user
  - set up ssh keys

- node
  - nvm

- zsh
  - link: .zshrc

## Opinions

Outsource dotfiles.

I am using https://github.com/skwp/dotfiles for zsh and vim.

## Laptop : T440s

• Intel Core i7-4600U Processor( 2.10GHz 1600MHz 4MB)
• 14.0" FHD IPS AntiGlare LED Backlight 1920x1080
• Intel HD 4400
• 8.0GB PC3-12800 DDR3L SDRAM 1600 MH
• Intel Dual Band Wireless-AC 7260
• Bluetooth Version 4.0

bought Oct 2014

- https://01.org/linuxgraphics
  - no longer needed?

---

## System


- Konsole
- vim.gtk3 (debian package)
- i3-gaps

terminal tools:
  - zsh / oh-my-zsh
  - ack
  - fd : https://github.com/sharkdp/fd
  - tree
  - feh
  - slurm
  - nmcli
  - alsamixer
  - cmus
  - powertop
  - xrandr

gui tools
  - pavucontol
  - gparted
  - filelight
  - vim (windows > single window mode)
  - polo (gui)

## Setup

- Vim
  - `update-alternatives --list vim` check which version of vim you have installed
    - found using vim-gtk worked ok, but was verion 7
  - `vim --version` check what current version of vim was built with
  - Commant-T ruby version: 
    - `~/.vim/bundle/Command-T/ruby/command-t`
    - something like : rbenv install new ruby, `ruby extconf.rb`, `make`

- Neovim
  - https://github.com/neovim/neovim
  - vundle
    - vim-plug : https://github.com/junegunn/vim-plug
      - carefully not where you install files / plugins!
    - // https://github.com/VundleVim/Vundle.vim

- Kubuntu - remap caps to esc
  - drop window menu / title bars
  - multiple desktops


## Resources:

- [Text Triumvirate](http://www.drbunsen.org/the-text-triumvirate/)
- https://github.com/powerline/powerline
- [Widdershin](https://github.com/Widdershin/dotfiles)

- rbenv
- nvm
  

## Old notes from Xubuntu

  - [Powerline fonts install](https://powerline.readthedocs.org/en/latest/installation/linux.html#fontconfig)
  - note font driectories in Xubuntu are : 
    - `/usr/share/fonts/X11/misc` : where you install font
    - `/etc/fonts/conf.avail` : install font .conf here then symlink to conf.d folder
  - I also deleted the symlink for the `70-no-bitmap-fonts.conf`
  - [remap caps keys  in xubuntu](http://askubuntu.com/questions/149971/how-do-you-remap-a-key-to-the-caps-lock-key-in-xubuntu)
  
  
