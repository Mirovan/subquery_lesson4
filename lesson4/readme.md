# SubQuery lesson 4

Author: Mirovan

#Install and run SubQuery

##Prepare install
```
sudo apt-get install mc
sudo apt-get install curl
sudo apt-get install git
sudo apt-get install npm
```

##Install Node.js
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
source ~/.bashrc
nvm list-remote
nvm install v16.13.2
npm install --global yarn
```

##Install SubQuery
```
npm install -g @subql/cli
```

##Clone project from GitHub
```

```

##Create and build project
```
subql init

yarn install
yarn codegen
yarn build
```
docker-compose pull && docker-compose up