# nBell

## 如何使用？

1. 打开 微信小程序【网铃】 创建一个监控任务。

2. 在小程序【OpenApi】板块中创建一个secret。

3. 点击生成的secret，设置该secret的查看权限。

4. 下载本项目的index.html，在文档中找到这个位置，并填写你的secret。

   ```
   /// 这里需要填写你的 OpenApi secret ///
   var SECRET = '';
   ```

5. 将本项目的index.html放置到您的网络空间中，无论是ECS还是静态OSS。

6. 尝试访问，查看效果！

示例效果
![图片](https://github.com/hope-meeter/nBell/blob/main/pic.jpg?raw=true)
