# ICCWAMTIP 网站生成器

使用静态网站生成工具 [Saber](https://github.com/egoist/saber) 构建的小波国际会议网站。

## 使用指南

1. 安装 [nodejs](https://nodejs.org/zh-cn/) v16.

2. 克隆这个仓库并进入这个目录
   ```shell
   $ git clone git@github.com:waveletlab-uestc/waveletlab-webbuilder.git
   $ cd waveletlab-webbuilder
   ```

3. 安装依赖
   ```shell
   $ npm i
   ```

4. 开发服务器
   ```shell
   $ npm run dev
   ```

## 打包部署

1. 打包
   ```shell
   $ npm run build
   ```

2. 部署

将 public 文件夹上传到服务器

<!-- 
4. 修改 `build.sh` 文件中的 `DEPLOY_PATH` 变量为部署的文件夹
   1. 克隆部署网站的仓库到某个位置
      ```shell
      $ git clone git@github.com:waveletlab-uestc/waveletlab-uestc.github.io.git
      $ # 采取 SSH 方式克隆 (git@github.com) 目的是为了 git push 方便
      ```
   2. 修改 `./build.sh` 中的 `DEPLOY_PATH` 为上述文件夹地址

5. 修改源码

   - 希望预览生成的页面通过命令，如果绑定服务器到指定主机和端口，修改 `./build.sh` 中的 `HOST` 和 `PORT` 变量
     ```shell
     $ ./build.sh dev
     ```

   Tips: 页面都在 `pages/` 目录下的文件中，支持 `Markdown` 和 `HTML` 语法

6. 修改完成后，构建并部署到网站上
   ```shell
   $ ./build.sh deploy
   ```

## build.sh

关于更多 `./build.sh` 的用法，请见 `./build.sh help`. -->
