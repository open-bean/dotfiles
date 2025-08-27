This repository contains my dotfiles which are mangaged using [stow](https://www.gnu.org/software/stow/).

The main branch conains all files used to configure my Linux desktop.

The MacOS branch contains the files used in my MacOS Workstation.

############
Installation
############

Ensure that git, and stow are installed on the machine.

Clone the repository in the home directory and create the corresponding symlinks using stow.

`https://github.com/open-bean/dotfiles.git`

`cd dotfiles`

`stow .`

if any errors occur try using `stow --adopt .`
