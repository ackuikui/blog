
# 项目介绍  
使用kpress，将md文章转化成静态html, 部署在服务器nginx上，形成个人blog。


## 下载后安装kpress
`npm install`

## 使用vscode本地编辑文章，记录图片等资源
- install vscode extension `paste image`  
- config vscode `setting.json`  
``` json
{
    "pasteImage.path": "${projectRoot}/blog/public/${currentFileNameWithoutExt}",
    "pasteImage.basePath": "${projectRoot}",
    "pasteImage.forceUnixStyleSeparator": true,
    "pasteImage.prefix": "/",
    "files.autoSave": "afterDelay",
}
```

## 部署
docs文件夹中写markdown文章后，`npm run build`，将生成blog文件夹上传到服务器
