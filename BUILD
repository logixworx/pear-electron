make sure you are on latest pear-pack
npm ls pear-pack
if not latest, try:
rm package-lock.json 
rm node_modules
then npm i again

----------
git clone https://github.com/logixworx/pear.git
git clone https://github.com/logixworx/pear-electron.git

cd ~/pear-electron
npm i
npm run prestage
pear stage dev
in package.json, update pear.assets.ui.link to staged full link pear://fork.length.key
npm pack
pear seed dev

cd ~/pear/examples/desktop
npm i ~/pear-electron/pear-electron-1.7.25.tgz

cd ~/pear
npm i
npm run bootstrap
./pear.dev run examples/desktop  # wait for a while

------------
https://github.com/holepunchto/pear-pack/commits/main/, in recent commit, targets is changed to hosts
Commits · holepunchto/pear-pack
Bundle and prebuild generation for Pear. Contribute to holepunchto/pear-pack development by creating an account on GitHub.
also, need to run with the local dev pear.dev from https://github.com/holepunchto/pear
because the latest commit in electron is using dynamic asset bundling which is not released yet in latest pear prod
