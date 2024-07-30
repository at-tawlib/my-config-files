# my-config-files

## init.vim
- use `nvim ~/.config/nvim/init.vim` to open the init.vim file
- If directory not available, create it.
- Install vimplug. Choose the neovim option [here](https://github.com/junegunn/vim-plug)
- To install the plugins, open init.vim with nvim and run `:PlugInstall`

- To install coc.nvim, goto to`/.config/nvim/plugged/coc.nvim`. If it is not there, create it
- Install yarn with `sudo npm install -g yarn`
- Then run `yarn install` . NB: important to run this code in this directory
- Run `yarn build`
- If you get error after `yarn build`, open neovim and run this command `:call coc#util#install()`

my configuration for neovim
it includes betty coding stye plugin

Search and install coc.nvim [here](https://stackoverflow.com/questions/69841916/neovim-coc-nvim-build-inderx-js-not-found-please-install-dependencies-and-com)
