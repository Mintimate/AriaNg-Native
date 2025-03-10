# 适配说明
- 适配了Mac下的arm64架构芯片
- 更改图标为BigSur风格的拟物图标

# 自行编译
如果想自己进行编译
- 下载项目源代码
- 确保自己电脑上安装了Node（NPM）

之后，进行编译安装：
```
$ npm install    
# For Windows
$ npm run publish:win
# For macOS on x64
$ npm run publish:osx --arch=x64
# For macOS on arm64
$ npm run publish:osx --arch=arm64
```

以下为上流：https://github.com/mayswind/AriaNg-Native 的Readme.md说明

# AriaNg Native
[![License](https://img.shields.io/github/license/mayswind/AriaNg-Native.svg?style=flat)](https://github.com/mayswind/AriaNg-Native/blob/master/LICENSE)
[![Lastest Release](https://img.shields.io/github/release/mayswind/AriaNg-Native.svg?style=flat)](https://github.com/mayswind/AriaNg-Native/releases)

## Introduction
AriaNg Native is a desktop application built by [Electron](https://github.com/electron/electron), containing full feature of [AriaNg](https://github.com/mayswind/AriaNg). You can run AriaNg Native on Windows or macOS without any browser. In addition, AriaNg Native also has many features that [AriaNg](https://github.com/mayswind/AriaNg) cannot implement.

#### Extra features
1. More user-friendly interface
2. Taskbar tray, supporting minimizing to tray
3. Command line arguments, supporting creating new task by opening file
4. Local file system operating support
5. File & Url drag support

## Introduction of AriaNg
Please visit [https://github.com/mayswind/AriaNg](https://github.com/mayswind/AriaNg) for more information.

## Screenshots
#### Windows
![AriaNg Native](https://raw.githubusercontent.com/mayswind/AriaNg-WebSite/master/screenshots/ariang_native_windows.png)

#### macOS
![AriaNg Native](https://raw.githubusercontent.com/mayswind/AriaNg-WebSite/master/screenshots/ariang_native_macos.png)

## Installation
#### Prebuilt release
Latest Release: [https://github.com/mayswind/AriaNg-Native/releases](https://github.com/mayswind/AriaNg-Native/releases)

#### Building from source
Make sure you have [Node.js](https://nodejs.org/) and [NPM](https://www.npmjs.com/) installed. Then download the source code, and follow these steps.
The builds will be placed in the dist directory.

## License
[MIT](https://github.com/mayswind/AriaNg-Native/blob/master/LICENSE)
