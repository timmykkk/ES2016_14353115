#  DOL����
## DOL����
>��װһЩ��Ҫ�Ļ���(ubuntuΪ��)��
- $	sudo apt-get update
- $	sudo apt-get install ant
- $	sudo apt-get install openjdk-7-jdk
- $	sudo apt-get install unzip
***
1.�����ļ�(ʹ��Vmware�������Ҳ���Դ������������������ȥhttp://jingyan.baidu.com/article/c33e3f48a5c153ea15cbb5b2.html
)��  

`sudo wget http://www.accellera.org/images/downloads/standards/systemc/systemc-2.3.1.tgz`
  
`  sudo wget http://www.tik.ee.ethz.ch/~shapes/downloads/dol_ethz.zip`
***
2.��ѹ�ļ�
- *�½�dol���ļ��� *
- `$	mkdir dol`
- ��dolethz.zip��ѹ�� dol�ļ�����
- `$	unzip dol_ethz.zip -d dol`
- ��ѹsystemc
- `$	tar -zxvf systemc-2.3.1.tgz`
- ��ѹ�����systemc-2.3.1��Ŀ¼��
- `$	cd systemc-2.3.1`
- ��**��**һ����*ʱ*�ļ���objdir
- `$	mkdir objdir`
- ������ļ���objdir
- `$	cd objdir`
- ����configure(�ܸ���ϵͳ�Ļ�������һ�²��������ڱ���)
- `$	../configure CXX=g++ --disable-async-updates`

![](http://c.hiphotos.baidu.com/baike/w%3D268%3Bg%3D0/sign=39dd17b7b74543a9f51bfdca262cedbf/b8389b504fc2d5620ff119aee71190ef77c66cfc.jpg)
