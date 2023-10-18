* 下载nvm
https://github.com/coreybutler/nvm-windows/releases

* 安装node
`nvm ls available`
`nvm install 16.20.0`
等待安装成功，修改 setting.txt,加快安装速度
node_mirror:npm.taobao.org/mirrors/node/
npm_mirror:npm.taobao.org/mirrors/npm/
`nvm use 16.20.0`
环境变量生效后 `node -v` 查看node是否安装成功