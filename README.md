# Before you set up

* Install the Neovim/nvim: `sudo apt install nvim`
* Then, install the **vim-plug**, plugin manager for nvim/vim
* Here's the link to the **vim-plug** GitHub: https://github.com/junegunn/vim-plug

## In addition, you need install in your system these program/application:
  - NPM: `sudo apt install npm`
    
      > After downloading, insert in terminal, this command: `sudo npm install -g neovim`
      
  - NodeJs: `sudo apt install nodejs`
      > If your node version is < 14 (then check node version using `node -v`), follow the below command in the terminal:
      * `sudo npm cache clean -f`
      * `sudo npm install -g n`
      * `sudo n stable`
      * Finishing this, your node version will be > 14, and now, you must follow the new steps by steps:
      * Go to this path `~/.local/share/nvim/plugged/coc.nvim`, and now (**you need to have installed the NPM**) enter this command in terminal: `npm install` and that should install everything necessary for coc (plugin) to run properly
  

## Inside the nvim, put this `:PlugInstall` in the command line, and wait for all plugins are installed

Therefore, all the plugins contained in the **ini.vim** will be working. Other pluging can be added or removed, editing the mentionated file

For more informations:
  * https://github.com/neoclide/coc.nvim/wiki/Install-coc.nvim
  * https://github.com/neoclide/coc.nvim
  * https://stackoverflow.com/questions/69841916/neovim-coc-nvim-build-inderx-js-not-found-please-install-dependencies-and-com

Author: Caio Cesar (Studant at the UFCG-Brazil)
