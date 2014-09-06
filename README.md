SCS-UEditor
===========

使用新浪云存储（SCS）保存 UEditor 中上传的图片、视频 、附件、涂鸦、等...

(基于 UEditor-1.4.3-utf8-php)

## 功能特性
* SCS 开关
* 单图、多图上传
* 在线管理
* 视频上传
* 附件上传
* 在线附件
* 涂鸦上传
* 截图上传（未测试）

## 使用方法

###1、下载 SCS-UEeditor

>#### [完整版下载](https://github.com/gmg137/SCS-UEditor/archive/master.zip)

>#### [插件版下载](https://github.com/gmg137/UEditor-SCS-plugin/archive/master.zip)

###2、完整版配置

- 解压下载后的压缩包，修改 ./SCS-UEditor/php/conf.php 文件



		$openscs = '0'; //是否启用SCS，1 为启用，0 为禁用

		$accessKey	= '';  //你的新浪SCS Access Key

		$secretKey	= '';  //你的新浪SCS Secret Key

		$bucket = "";   //你的 bucket 名称



###3、插件版配置

- 解压下载后的压缩包，将所有文件复制到你的 ueditor/php/ 文件夹下覆盖原文件。然后修改 ueditor/php/conf.php 文件（注意：UEditor 版本应 >= 1.4.2）



		$openscs = '0'; //是否启用SCS，1 为启用，0 为禁用

		$accessKey	= '';  //你的新浪SCS Access Key

		$secretKey	= '';  //你的新浪SCS Secret Key

		$bucket = "";   //你的 bucket 名称
    

##截图
![2014-09-06 16 18 10](https://cloud.githubusercontent.com/assets/6460323/4174895/5403aae6-35b0-11e4-9fbc-50b8cd7c625b.png)
![2014-09-06 16 20 46](https://cloud.githubusercontent.com/assets/6460323/4174891/4d232f3a-35b0-11e4-95da-80bb85bfac6d.png)
![2014-09-06 16 28 36](https://cloud.githubusercontent.com/assets/6460323/4174918/aaf505ec-35b1-11e4-93da-65648a07dcc4.png)

   
##其它

[UEditor 主页](http://ueditor.baidu.com/website/)

[新浪云存储主页](http://open.sinastorage.com/)

[申请新浪云存储邀请码](http://weibo.com/cloudtrans)
