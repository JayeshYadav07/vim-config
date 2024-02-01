# vim-config

[source](https://www.freecodecamp.org/news/vimrc-configuration-guide-customize-your-vim-editor/)

### follow the command

```sh

    cd ~
    
    #install git
    yum install git -y

    #creat the required files and folders
    mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged
    touch ~/.vimrc

    # clone the repo for config file
    git clone https://github.com/JayeshYadav07/vim-config.git
    
    #copy the config file
    cp vim-config/.vim .vimrc
    cd ~/.vim/colors

    #Install colorscheme molokai
    curl -o molokai.vim https://raw.githubusercontent.com/tomasr/molokai/master/colors/molokai.vim

    #add colorscheme to .vimrc files
    :colorscheme molokai
    
    #Enjoy your vim

```
