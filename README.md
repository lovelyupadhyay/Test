Realize Reader

Setting up development environment

install node.js
install gulp & bower
if necessary, install jspm-git (although this should be in the package.json already):
npm i -D jspm-git
npm install -dev jspm
set up the pearson jspm registry by executing:
jspm registry create pearson jspm-git
You will then receive the following prompts:
Enter the base URL of your git server: ssh://git@bitbucket.pearson.com
Set advanced configurations?: no
execute npm install
execute gulp build, the follow the steps below in 'Run the app in Chrome'.