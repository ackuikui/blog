# Paste Image
使用该扩展程序，鉴于需修改配置才能指定目录，记录一下。


### 1. vscode安装`Paste Image`扩展程序

### 2. 修改vscode设置，增加如这几行
![](/public/paste-image/2023-10-17-18-02-49.png)
``` json
{
    "pasteImage.path": "${projectRoot}/public/${currentFileNameWithoutExt}",
    "pasteImage.basePath": "${projectRoot}",
    "pasteImage.forceUnixStyleSeparator": true,
    "pasteImage.prefix": "/",
    "files.autoSave": "afterDelay",
}
```

### 3.使用剪切版图片，自动存储
- 截屏
win11 `win + shift + S`
mac `command + shift + 4`

- 粘贴
win `ctrl + alt + v` 
