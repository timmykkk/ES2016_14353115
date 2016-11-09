#  DOL配置
## DOL配置
>安装一些必要的环境(ubuntu为例)：
- $    sudo apt-get update
- $	sudo apt-get install ant
- $	sudo apt-get install openjdk-7-jdk
- $	sudo apt-get install unzip
***
1.下载文件(使用Vmware虚拟机，也可以从主机拷贝到虚拟机中去

`sudo wget http://www.accellera.org/images/downloads/standards/systemc/systemc-2.3.1.tgz`
  
`sudo wget http://www.tik.ee.ethz.ch/~shapes/downloads/dol_ethz.zip`
***
2.解压文件
  
  *新建dol的文件夹 *
  
  `$	mkdir dol`
  
  将dolethz.zip解压到 dol文件夹中
  
  `$	unzip dol_ethz.zip -d dol`
  
  解压systemc
  
  `$	tar -zxvf systemc-2.3.1.tgz`
  
  解压后进入systemc-2.3.1的目录下
  
  `$	cd systemc-2.3.1`
  
  新**建**一个临*时*文件夹objdir
  
  `$	mkdir objdir`
  
  进入该文件夹objdir
  
  `$	cd objdir`
  
  运行configure(能根据系统的环境设置一下参数，用于编译)
  
  `$	../configure CXX=g++ --disable-async-updates`

