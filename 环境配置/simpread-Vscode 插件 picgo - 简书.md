> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.jianshu.com](https://www.jianshu.com/p/937897f6f4f5)

VsPicGo Notes
=============

作用
--

*   使用各种图床，在 vscode 中使用快捷键快速将图片转换成 url 插入文档中
    
*   个人使用 github 的图床，需要自己手动创建一个 github 仓库
    

设置
--

1.  vscode 中下载 picgo 插件
    
2.  在 github 上新建一个 repository 并生成一个 token
    
    *   如何生成一个 token:
        *   github 网站 -> Settings -> Developer Settings -> Personal Access tokens -> Generate new token -> 记住此 token
3.  在 vscode 中设置 githb 图层
    

*   [图片上传失败...(image-36b85c-1576979473861)]
    *   picgo setting:
        *   Pic Bed Current 选择 github
        *   Path：填写新建 github 仓库的路径 例如: `VscodeImages`
        *   Repo: 用户名 / 仓库名， 比如: `baby-jie/MarkdownImages`
        *   Token: 第二步骤在 github 网站上设置的 token 填入其中即可

4.  上传测试

快捷键
---

*   uploading an image from clipoard: `Ctrl + Alt + U`
    
*   uploading images from explorer: `Ctrl + Alt + E`
    
*   uploading an image from input box: `Ctrl + Alt + O`