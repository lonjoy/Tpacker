## 下载

- windows:[download](https://github.com/taobao-wd/Tpacker/raw/master/T-Packer_1.0.1.zip)
- linux:[download](https://github.com/taobao-wd/Tpacker/raw/master/yjsmin)

## 环境依赖

工具依赖java环境，安装前先确认已经安装java环境并配好JAVA_HOME环境变量

![img](http://img01.taobaocdn.com/tps/i1/T1Zm8ZXd4kXXXXXXXX-394-407.png)

## 安装

配好JAVA_HOME后，安装T-Packer.exe

![img](http://img02.taobaocdn.com/tps/i2/T18mRZXaJnXXXXXXXX-511-400.png)

安装完毕后，运行桌面快捷方式 T-Packer

![img](http://img03.taobaocdn.com/tps/i3/T1m_VZXolaXXXXXXXX-206-305.png)

给定源目录和目标目录，点击Pack ，进行批量压缩

![img](http://img03.taobaocdn.com/tps/i3/T1u_0ZXbdgXXXXXXXX-709-80.png)

压缩完成后会弹出压缩后的目录。

## linux 命令行脚本

脚本依赖java环境，请安装jdk并配置JAVA_HOME

拷贝 yjsmin 到 `/usr/bin/`目录

拷贝 `yuicompressor-x.y.z.jar`,`jsmin.jar` 到 `/usr/bin/` 目录

进入到要执行压缩的目录,执行

	yjsmin 目标目录

## 安装须知

- windows安装程序默认安装在C:\TBTools\Packer
- css 压缩采用 yuicompressor,js 压缩采用 jsmin，并做 native2ascii 转码，css 文件转换为 \xxxx，js文件转换为 \uxxxx
- 支持源文件的GBK和UTF-8格式
- 生成.source.js或.source.css源文件
- 目前程序为测试版，不保证一定好用。
