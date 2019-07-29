https://raw.githubusercontent.com/larry0220/nlp_practice/master/README.md

https://jsvine.github.io/intro-to-visidata/_downloads/021660fd27755eb60fd2ce4ea3d76a91/faa-wildlife-strikes.csv

##### http://mirror.centos.org/centos/7/os/x86_64/RPM-GPG-KEY-CentOS-7
##### conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

mkdir -p ~/.local/share/fonts
cd ~/.local/share/fonts && curl -fLo "Droid Sans Mono for Powerline Nerd Font Complete.otf" https://github.com/ryanoasis/nerd-fonts/raw/master/patched-fonts/DroidSansMono/complete/Droid%20Sans%20Mono%20Nerd%20Font%20Complete.otf



export PATH="/home/linuxbrew/.linuxbrew/bin:/home/linuxbrew/.linuxbrew/sbin:$PATH"

# Set name of the theme to load --- if set to "random", it will
# load a random theme each time oh-my-zsh is loaded, in which case,
# to know which specific one was loaded, run: echo $RANDOM_THEME
# See https://github.com/robbyrussell/oh-my-zsh/wiki/Themes
DISABLE_AUTO_UPDATE="true"
# ZSH_THEME="robbyrussell"

source ~/antigen.zsh

# Load the oh-my-zsh's library.
antigen use oh-my-zsh

# Bundles from the default repo (robbyrussell's oh-my-zsh).
antigen bundle git

# Syntax highlighting bundle.
antigen bundle zsh-users/zsh-syntax-highlighting
antigen bundle zsh-users/zsh-completions
# antigen bundle zsh-users/zsh-autosuggestions

# Load the theme.
antigen theme robbyrussell
# antigen theme denysdovhan/spaceship-prompt

# Tell Antigen that you're done.
antigen apply





. ~/.my_tools/z/z.sh

alias ls="lsd"
alias la="ls -a"
alias ll="ls -l"
alias l="ls -lha"
alias lt="ls --tree"

alias lynx="lynx -vikeys"

alias bat="bat -p"





source /dockerstartup/generate_container_user

export NO_VNC_HOME="/usr/share/usr/local/share/noVNCdim"
export NO_VNC_PORT="6901"
export VNC_COL_DEPTH=24
export VNC_PORT="5901"
export VNC_PW=""
export VNC_RESOLUTION=1024x768
export VNC_VIEW_ONLY=false



yum remove docker  docker-client docker-client-latest docker-common docker-latest \
                  docker-latest-logrotate docker-logrotate docker-selinux docker-engine-selinux docker-engine
                  
                  
                  
wget --header="Host: doc-08-1g-docs.googleusercontent.com" --header="User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Ubuntu Chromium/75.0.3770.90 Chrome/75.0.3770.90 Safari/537.36" --header="Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3" --header="Accept-Language: en-US,en;q=0.9" --header="Referer: https://drive.google.com/uc?id=1HiYhgA89XcWmLEDw7zFP6NeXqH6mcTmw&export=download" "https://doc-08-1g-docs.googleusercontent.com/docs/securesc/ha0ro937gcuc7l7deffksulhg5h7mbp1/a16t2lb8pat884frpihc5tutm7o0g64a/1564394400000/06784692563868000974/*/1HiYhgA89XcWmLEDw7zFP6NeXqH6mcTmw?e=download" -O "vnc_atom_0729.tar.gz" -c
