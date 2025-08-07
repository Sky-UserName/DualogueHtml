# 最后的轻语

中文｜[English](./README_EN.md)

以特殊的方式对某人说出你想要说的内容。

本项目预览页面：<https://friendly-paprenjak-ad64b7.netlify.app/>

**项目亮点：**

1. 精心设计的文字动效与浪漫飘逸的气球动画
2. 通过简单修改`customize.json`文件即可自定义所有文字内容、图片素材、背景音乐及字体样式
3. 点击页面任意位置都会绽放绚丽的烟花特效
4. 自动播放优美的背景音乐,营造温馨浪漫的氛围
5. 使用现代化的 rspack 构建项目，性能更优

## 一些你或许想了解的项目背景

用于祝福特别的人或者恋人生日快乐，烘托浪漫气氛,关于项目背后的故事。

## 使用方法

- Netlify 部署（国内用户推荐，不被墙）

   [![Deploy with NEtlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/abandon888/HappyBirthday)

可以修改文字，图片，背景音乐,字体等，但有一些注意的地方：

1. 仅修改 customize.json 文件，不要修改其它文件，否则可能会导致页面无法正常显示。
2. 音乐替换时注意重命名为相同名称的音乐文件或注意修改 json 文件中路径，如我这里是`bgMusic.mp3`
3. 图片替换时生日帽子可能会偏，建议修剪图片尺寸和原图片相同，以确保最佳观赏效果。
## 本地开发/预览

项目使用 npm 作为包管理器，请确保本地已经配置 node 环境，否则请自行安装，node 环境检验如下：

```
$ node -v
v22.2.1
```

然后安装依赖：

```
npm install
```

运行：

```
npm run start
