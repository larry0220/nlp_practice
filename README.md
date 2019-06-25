##### http://mirror.centos.org/centos/7/os/x86_64/RPM-GPG-KEY-CentOS-7
##### conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

##### Add the package repositories
distribution=$(. /etc/os-release;echo $ID$VERSION_ID)
curl -s -L https://nvidia.github.io/nvidia-docker/$distribution/nvidia-docker.repo | \
  sudo tee /etc/yum.repos.d/nvidia-docker.repo
