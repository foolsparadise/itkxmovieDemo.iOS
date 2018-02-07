# kxmovieDemo
## 注意：  
当前使用环境：MacOS High Sierra Version 10.13.2 (17C205) ，Xcode9.2 ，SDK11.2
## howto  
原工程 https://github.com/kolyvan/kxmovie 同时，我fork了一份  
使用kxmovie工程打包ffmpeg  
下载 https://github.com/FFmpeg/FFmpeg/releases 下载最新ffmpeg的zip包，比如我下载的是 Dec 31, 2017 n2.4.14 ，并解压到kxmovie工程根目录下，目录名为 FFmpeg  
下载 https://github.com/libav/gas-preprocessor 中的gas-preprocessor.pl，放到kxmovie工程根目录下，gas-preprocessor目录中，文件名为gas-preprocessor.pl  
使用我修改后的Rakefile文件，覆盖kxmovie工程根目录中的Rakefile文件  
执行命令 sudo rake  
