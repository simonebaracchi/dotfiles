## Installation

     cd
     git init .
     git remote add origin https://github.com/simonebaracchi/dotfiles.git
     git fetch
     git checkout origin/master -ft

## Configuration

`molokai.vim` should be moved somewhere around `/usr/share/vim/vim*/colors`

Once moved, consider cleanup:


    # rm molokai.vim README.md
    # git update-index --assume-unchanged molokai.vim README.md


