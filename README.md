##### http://mirror.centos.org/centos/7/os/x86_64/RPM-GPG-KEY-CentOS-7
##### conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"


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
