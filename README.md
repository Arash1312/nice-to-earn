
# Install Nodejs, npm, yarn
sudo apt update
sudo curl -fsSL https://deb.nodesource.com/setup_22.x | sudo -E bash -
sudo apt install -y nodejs
node -v
npm install -g yarn
yarn -v# Packages:
sudo apt update && sudo apt upgrade -y
sudo apt install screen curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y


# Install Hardhat
sudo npm install -g hardhat
