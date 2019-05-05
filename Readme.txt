UBUNTU Gitea install [LINUX GIT SERVER]

資料來源:https://www.youtube.com/watch?v=dV5XjevX_tY

GITHUB:https://github.com/jash-git/UBUNTU-Gitea-install

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install git-core

git --version

#https://docs.gitea.io
#https://docs.gitea.io/zh-tw/install-from-binary/
#https://docs.gitea.io/en-us/install-from-binary/

wget -O gitea https://dl.gitea.io/gitea/1.7.0/gitea-1.7.0-linux-amd64

sudo chmod +x gitea

./gitea web
