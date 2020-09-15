# composer
guohua_composer
将平时工作中常用的PHP代码打包成一个composer 供自己使用 

安装方法
1、不要使用 composer require 进行安装 容易安装失败
2、在项目位置 新建一个 composer.json 文件 
  2.1:写入下面代码
    {
      "require": {
      "hua01234567899/guohua_composer": "dev-master"
    }
    }
  2.2: 在改目录执行 composer insatll 命令 

