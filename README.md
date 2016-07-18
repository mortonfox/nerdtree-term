# nerdtree-term

## Introduction

This NERDTree plugin adds a menu item to open the selected folder in Terminal.
(i.e. open a shell window and cd to that folder)

## Installation

### Pathogen

Use the following commands:

    cd ~/.vim/bundle
    git clone https://github.com/mortonfox/nerdtree-term.git

### Vundle

Add the following to your vimrc:

    Plugin 'mortonfox/nerdtree-term'

Install with ```:PluginInstall```.

### Manual Installation

Copy the ```terminal_menu_item.vim``` file to ```~/.vim/nerdtree_plugin/```
(*nix) or ```~/vimfiles/nerdtree_plugin``` (Windows).

## Usage

In the NERDTree window, select the desired folder and then
type ```m``` and ```t``` to open the Terminal session.
