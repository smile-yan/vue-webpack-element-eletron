# vue-webpack-element-eletron

> A Vue.js project with webpack, element and eletron

## Quick-start

Firstly, you should make sure that you have installed node.js and electron.

```bash
# install all dependencies 
cnpm install 

# build all htlm/css js
npm run build

# quick-start electron
electron dist
```
# Serve at localhost:8080
```bash
# install
cnpm install

# build all htlm/css js
npm run build

# run dev at localhost:8080
npm run dev
```

## Build unpacked files with .exe

```bash
# install
cnpm install

# build all htlm/css js
npm run build

# package
node_modules\.bin\electron-packager dist HelloWorld --win --out win --arch=x64 --app-version=0.0.1  --electron-version=6.0.2
```

## Package installer 

```bash
# install
cnpm install

# build all htlm/css js
npm run build

# download electron-builder into %LOCALAPPDATA%\electron\Cache or ...\electron-builder\Cache
# for example %LOCALAPPDATA%\electron\Cache\electron-v4.1.0-win32-x64.zip 
# https://npm.taobao.org/mirrors/electron/4.1.0/
# for others that can't download in that address above, please download from github and unpack into electron-builder\Cache
# for example, 
# for nsis-3.0.3.2.7z you should let nsis-3.0.3.2/ in electron-builder/nsis/
# for nsis-resources-3.3.0.7z you should let nsis-resources-3.3.0/ in electron-builder/nsis/        
# for winCodeSign-2.4.0.7z you should let winCodeSign-2.4.0/ in electron-builder/winCodeSign
# run script to package exe
npm run pack:win
```

> smile - yan
>
> 2020.02.02

