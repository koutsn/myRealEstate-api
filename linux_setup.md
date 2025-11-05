# Install maven
sudo apt install maven

# Install Nodejs
sudo apt install curl

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

source ~/.bashrc

nvm --version

nvm install 22

nvm use 22

npm install -g npm@latest


#### Redocly Installation
npm install redoc

npm install -g @redocly/cli

npx @redocly/cli --version


### Redocly Configuration
Setup in redocly.yaml

    apis:
      sample@v1:
        root: <file.yaml>


### Test YAML
redocly lint