Requirements
-------------
* xcode
* [homebrew](http://mxcl.github.com/homebrew/)
* node5+
* npm
* php7+

Installation
-------------
* xcode-select --install
* /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
* cd ~
* git clone --recursive git@github.com:m0neyball/dotfiles.git ~/.vim
* cd ~/.vim
* brew install bash-completion git node homebrew/php/composer homebrew/php/php70
* npm -g install instant-markdown-d
* ln -s ~/.vim/vimrc ~/.vimrc
* ln -s ~/.vim/gitconfig ~/.gitconfig
* ln -s ~/.vim/bash_profile ~/.bash_profile

**root**
* ln -s ~{Username}/.vim .
* ln -s ~{Username}/.vim/vimrc .vimrc
* ln -s ~{Username}/.vim/gitconfig ~/.gitconfig
* ln -s ~{Username}/vim/bash_profile .profile

Update git config
----------------------
* ADD personal git config `~/.gitconfig`
* ADD homebrew Github API into bash_profile `HOMEBREW_GITHUB_API_TOKEN`

Chrome extension
----------------
* [instant-markdown](https://chrome.google.com/webstore/detail/markdown-preview/jmchmkecamhbiokiopfpnfgbidieafmd?hl=zh-TW)
* [pretty-js](https://chrome.google.com/webstore/detail/pretty-beautiful-javascri/piekbefgpgdecckjcpffhnacjflfoddg)
* [full-page-screen-capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
* [json-formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=zh-TW)
* [hangouts](https://chrome.google.com/webstore/detail/google-hangouts/nckgahadagoaajjgafhacjanaoiihapd?hl=zh-TW)

Referances
-----
* [vimcasts](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/) -- vimcasts.org
* [vim-instant-markdown](https://github.com/suan/vim-instant-markdown.git) -- vim-instant-markdown
