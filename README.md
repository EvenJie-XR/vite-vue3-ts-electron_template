# Vue3 + Vite + Typescript + Electron

**已完成的目标:**
1. 使用pnpm dev时会打开一个桌面端窗口并展示你的网页内容
2. 使用pnpm build能够成功完成windows的打包(目前只测试了windows环境)

**运行项目:**
1. ```pnpm install```安装项目依赖
2. ```pnpm dev```运行项目。你将看到一个桌面端窗口里面展示了网页的内容
3. ```pnpm build```打包项目。在打包项目之前请你在你本机的```.npmrc```文件中添加electron-builder的配置，防止因为国内环境的影响导致打包失败，配置如下：
   ```
    # 在项目根目录创建 .npmrc 文件，添加：
    ELECTRON_MIRROR=https://npmmirror.com/mirrors/electron/
   ```
4. 打包完成后你会在release文件夹下得到你的打包结果（它包含了免安装的版本和安装包的版本，你可以根据你的需要分享你的作品。祝你玩的开心，Bye~）