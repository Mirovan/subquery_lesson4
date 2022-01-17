# SubQuery lesson 4

Author: Mirovan

## Prepare install
```
sudo apt-get install mc
sudo apt-get install curl
sudo apt-get install git
sudo apt-get install npm
apt install docker-compose
```

## Install Node.js
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v16.13.2
npm install --global yarn
```

## Install SubQuery
```
npm install -g @subql/cli
```

## Clone project from GitHub
```
git clone https://github.com/subquery/tutorials-simple-aggregation_v2.git
```

## Create and build project
```
yarn install
yarn codegen
yarn build
```

## Run project
```
docker-compose pull && docker-compose up
```