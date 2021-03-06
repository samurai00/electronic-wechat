# CHANGELOG

**v1.2 (2016.04.21)**

1. 新增 更新检测模块，应用内即可检查更新

2. 新增 公众号文章的第三方分享功能。现支持一键分享到微博、QQ 空间、Facebook、Twitter、Evernote 和邮件 (感谢 @oblank 的贡献)

3. 新增 群聊 @ 提及成员功能，但收到提醒需要服务端支持 (感谢 @iamcc 的贡献)

4. 优化 登录界面使用单独的尺寸 (感谢 @xnfa 的贡献)

5. 优化 修改 OS X 下隐藏其他窗口的快捷键为 `Command+Alt+H` 。

6. 优化 Linux 下可执行文件文件名使用小写字母，去除空格。

7. 优化 Linux 下使用彩色图标。

8. 升级 `electron-prebuilt` 版本至 `0.37.6` ， `electron-packager` 版本至 `7.0.0`。

9. ~~降级 Emoji贴纸显示的功能。由于微信协议调整和官方代码缺陷，现有商店内贴纸及部分个人收藏的贴纸无法显示。后续跟进微信的修复进行调整。~~ (Update: 微信已修复，贴纸均可正常显示)

   ​

**v1.1 (2016.03.17)**

1. 新增 OS X 和 Linux 下的托盘菜单，点击可进入应用、退出应用 (仅Linux) (感谢 @iamcc 和 @wenLiangcan 的贡献)
2. 新增 cnpm 镜像提醒
3. 优化 应用的退出逻辑，Cmd+Q 退出应用，Cmd+W 或点击关闭隐藏应用
4. 优化 OS X 和 Linux 下的应用菜单显示
5. 优化 Emoji贴纸的实现方式，避免滑动时内容抖动，无法回到底部
6. 优化 接管应用刷新的逻辑，Cmd+R 重新加载页面
7. 优化 OS X 下 build 后将应用拷贝到 Application 文件夹
8. 优化 Linux 下使用 Ctrl+Shift+I 打开开发者工具 (感谢 @wenLiangcan 的贡献)
9. 修复 错误的微信站内重定向 (感谢 @gucheen 的贡献)
10. 修复 Linux 下应用图标的显示
11. 修复 聊天列表滑动性能问题
12. 修复 公众号新窗口打开报错 (感谢 @gzzhanghao 的贡献)

**v1.0 (2016.03.01)**

1. 新增 阻止消息撤回的功能 (感谢 @arrowrowe 的贡献)
2. 新增 引入了 Travis CI 和 Gitter.im
3. 优化 贴纸显示的实现方式 (感谢 @arrowrowe 的贡献)
4. 优化 build 脚本 (感谢 @gaocegege, @viko16 和 @htc550605125 的贡献)
5. 优化 Linux 下自动隐藏菜单 (感谢 @wenLiangcan 的贡献)
6. 优化 Linux 下用户头像的显示
7. 优化 禁用缩放、选中文本、默认光标

**v0.1 (2016.02.19)**

1. Create the project.
2. Auto resize web content.
3. Drag to send pictures.
4. Open inhibited links without additional redirect.
