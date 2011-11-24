![logo](http://img04.taobaocdn.com/tps/i4/T1rEB3Xm4wXXXXXXXX-496-96.png)

- Created by [拔赤](http://jayli.github.com)
- License: [http://www.opensource.org/licenses/bsd-license](http://www.opensource.org/licenses/bsd-license)

下载

- windows(新版):[T-Packer-minifier-1.0.1.exe](https://github.com/jayli/Tpacker/raw/master/T-Packer-minifier-1.0.1.exe)
- linux(新版):[download](https://github.com/jayli/Tpacker/raw/master/tpack)
- windows(旧版):[T-Packer.exe](https://github.com/jayli/Tpacker/raw/master/T-Packer.exe)

旧版：将源文件压缩成为目标压缩文件和.source.js/css

新版：将源文件压缩为-min.js/css和保留源文件(推荐)

## 流行批量压缩工具比较

![img](http://jayli.github.com/gallery/bird/compressor.png)

## 环境依赖

工具依赖java环境，安装前先确认已经安装java环境并配好JAVA_HOME环境变量

![img](http://img01.taobaocdn.com/tps/i1/T1Zm8ZXd4kXXXXXXXX-394-407.png)

## 安装

配好JAVA_HOME后，安装T-Packer-minify.exe

![img](http://img02.taobaocdn.com/tps/i2/T18mRZXaJnXXXXXXXX-511-400.png)

安装完毕后，运行桌面快捷方式 T-Packer

![img](http://img03.taobaocdn.com/tps/i3/T1m_VZXolaXXXXXXXX-206-305.png)

给定源目录和目标目录，点击Pack ，进行批量压缩

![img](http://img03.taobaocdn.com/tps/i3/T1u_0ZXbdgXXXXXXXX-709-80.png)

也可以通过右键->发送到->TPacker-compressor，对单个(多个)文件进行压缩，生成"-min.js/css"文件

![右键压缩](http://img02.taobaocdn.com/tps/i2/T1Dfd3XbBzXXXXXXXX-478-99.png)

压缩完成后会弹出压缩后的目录。

## linux 命令行脚本

脚本依赖java环境，请安装jdk并配置JAVA_HOME

拷贝 tpack,cssmin,jsmin到 `/usr/bin/`目录(或者~/bin/目录)

拷贝 `yuicompressor-x.y.z.jar`,`jsmin.jar` 到 `/usr/bin/` 目录

进入到要执行压缩的目录,执行

	tpack 目标目录

单文件压缩
	
	cssmin 源文件 压缩为的文件
	jsmin 源文件 压缩为的文件

## 安装须知

- windows安装程序默认安装在C:\TBTools\Packer
- css 压缩采用 yuicompressor,js 压缩采用 jsmin，并做 native2ascii 转码，css 文件转换为 \xxxx，js文件转换为 \uxxxx
- 支持源文件的GBK和UTF-8格式
- 生成源文件和-min.js或者-min.css文件(旧版打包工具生成source.js或.source.css源文件)
- 目前程序为测试版，不保证一定好用。
