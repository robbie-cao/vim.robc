# Vim Configuration

**[Robbie Cao](<mailto: robbie.cao@gmail.com>)**

## Information

This is the .vimrc file of [Robbie Cao](<mailto: robbie.cao@gmail.com>).
Much of it is beneficial for general use, I would recommend
picking out the parts you want and understand.

Major of those config are from:

- [spf13](https://github.com/spf13)/[spf13-vim](https://github.com/spf13/spf13-vim)
- [wklken](https://github.com/wklken)/[k-vim](https://github.com/wklken/k-vim)

Thank [spf13](https://github.com/spf13) and [wklken](https://github.com/wklken) !

## Installation

1. Clone a copy to your local

    ```
    $ git clone git@github.com:robbie-cao/vim.robc.git
    ```

2. Install dependence packages
    - ctags, ag(the_silver_searcher)
    
    - ubuntu

       ```
       $ sudo apt-get install ctags
       $ sudo apt-get install build-essential cmake python-dev  #编译YCM自动补全插件依赖
       $ sudo apt-get install silversearcher-ag
       ```
    
    - mac

       ```
       $ brew install ctags
       $ brew install the_silver_searcher
       ```

3. Run install.sh

    ```
    $ cd config-vim
    $ ./install.sh --clang-completer
    ```

Enjoy!

## Documentation



## Know Issues
1. MarkdownPreview has problem during Vim start after update python with brew (brew update & brew install python). [Log](http://git.io/vCjBM)
2. InstantMarkdownPreview works with Firefox, but has issue with Chrome.



## TODO
1. Move plugin enable/disable config to vimrc or a sperate config file
2. Optimize config on file types
3. More


## Contribution
If you would like to help making it better, feel free to fork it. Any patches are welcome.

## About Me


