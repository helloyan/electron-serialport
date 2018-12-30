# electron-serialport

一个能运行的electron-serialport例程

## 依赖

```bash
# 安装node-gyp，建议全局
npm install -g node-gyp
## 很多无法编译的是缺少这个，时间不短，耐心等待，另外如果机器已有py27，可以设置进path，安装时会自动跳过
npm install -g windows-build-tools
```

## 使用

```bash
# clone源
git clone https://github.com/helloyan/electron-serialport.git
cd electron-serialport
# msvs_version参数视windows-build-tools安装的版本而定，默认是2017
npm install --msvs_version=2017
# 运行
npm start
```

更多请参照fork源 [electron-serialport](https://github.com/nodebots/electron-serialport).

#### License [CC0 1.0 (Public Domain)](LICENSE.md)
