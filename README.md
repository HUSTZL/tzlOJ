# tzlOJ

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install docker docker-compose
sudo apt-get install wget
git clone git@github.com:HUSTZL/tzlOJ.git
nvm install v8.12.0
nvm use 8.12.0
node -v
npm -v
cd OnlineJudge
sudo docker build -f Dockerfile -t oj-backimg .
docker-compose -f rpj.yml up -d
cd ..
cd OnlineJudgeFE
npm install
export NODE_ENV=development 
npm run build:dll
npm run dev
```
