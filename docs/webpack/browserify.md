`npm install -g browserify`


![](/source/img/browserify/2023-05-30-00-08-35.png)

> browserify : 无法加载文件 D:\Program\nodejs\browserify.ps1，因为在此系统上禁止运行脚本。

管理员打开powsershell
`Get-ExecutionPolicy`

* Restricted: 不载入配置文件, 不执行脚本. "Restricted"是默认值.
* AllSigned: 所有的配置文件和脚本必须通过信任的出版商签名(trusted publisher), 这里所指的脚本页包括你在本地计算机上创建的脚本.
* RemoteSigned: 所有从互联网上下载的脚本必须通过信任的出版商签名(trusted publisher).
* Unrestricted: 载入所有的配置文件和脚本. 如果你运行了一个从互联网上下载且没有数字签名的脚本, 在执行前你都会被提示是否执行

`Set-ExecutionPolicy RemoteSigned`
![](/source/img/browserify/2023-05-30-00-09-35.png)

`browserify index > bundle.js`
![](/source/img/browserify/2023-05-31-00-03-29.png)