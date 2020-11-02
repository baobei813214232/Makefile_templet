Makefile_templet -- Makefile templet for Linux
=======================

[![Build Status](https://travis-ci.org/latelee/Makefile_templet.svg?branch=master)](https://travis-ci.org/latelee/Makefile_templet)
[![GitHub stars](https://img.shields.io/github/stars/latelee/Makefile_templet.svg)](https://github.com/latelee/Makefile_templet)[![GitHub forks](https://img.shields.io/github/forks/latelee/Makefile_templet.svg)](https://github.com/latelee/Makefile_templet)

Stargazers over time  
[![Stargazers over time](https://starcharts.herokuapp.com/latelee/Makefile_templet.svg)](https://starcharts.herokuapp.com/latelee/Makefile_templet)

PROJECT
=======================
files for Makefile
* Makefile��the default Makefile, for all files in ONE directory(c or c++), auto detect the target(.so or .a or binary file)
* one_dir_project��Makefile demo
* mult_dir_project��Makefile for multi directory(ref u-boot, out of date)
* mult_dir_project_new��a new version for multi directory(not u-boot)
* linux_driver��Makefile for linux driver demo
* stm32_project: Makefile for stm32(using arm-none-eabi-gcc)

USAGE
=======================
* Just put Makefile under the project directory, and just make it.
* For more, you may want to modify head files directory, source files directory, compiler flags and the target file name.
* What to modify? see "!!!=== " in the Makefile. If you want to delete the .a or .so files, specify the name under clean.
* By default, type��make
* For more compile information, type:make V=1  (V is uppercase)
* For debug version, type: make debug=y
* For release version, type: make debug=n
* For cross compile, type��make CROSS_COMPILE=arm-linux-

NOTES
=======================
For the Linux kernel, you need to specify the .o files under Makefile.

COPYRIGHT
=======================
Copyright by Late Lee, but anyone can use it for any purporse(study or bussiness), any problems, pls let me know.

AUTHOR
=======================
Late Lee (li@latelee.org) <br>

[CST studio](http://www.latelee.org) welcome donate!

last release: <br>
2018.12.11 <br>


Makefile_templet -- Linux������Makefileģ��
=======================

����˵��
=======================
���ֿ����Makefileʾ����
* Makefile��Ĭ�ϵ�Makefile�����Ŀ¼�������ļ�(c/c++)������Ŀ���ļ������ǿ��ļ����ǿ�ִ���ļ���
* one_dir_project����Ŀ¼����ʾ��
* mult_dir_project����Ŀ¼����ʾ��(�ο�uboot�ģ��ݲ�����)
* mult_dir_project_new���ɵ�Ŀ¼���̵�Makefile������ɣ�������uboot�汾������hello��Ŀ¼Ϊ����ʽ��  
* mult_dir_project_new1���������ƣ����м����ʽ���Զ������汾��ͷ�ļ�
* mult_dir_project_new2�����������ƣ����м�⣬����������Ŀ¼���Զ�����Դ�룬���Ϊ2��  
* linux_driver��linux������Makefileģ�弰�����ʾ����
* stm32_project: STM32��Makefile(ʹ��arm-none-eabi-gcc)

�÷�
=======================
* Ĭ������£�ֱ���ڽ���Makefile�ŵ���һ�Ĺ���Ŀ¼��make���ɡ�
* ���ݹ���ʵ��������޸�ͷ�ļ�����Ŀ¼��Դ��Ŀ¼������ѡ��(����Ӷ�̬/��̬��)���Լ������ļ�����
* Ҫ�޸ĵĵط��Ѿ�ʹ�� !!!=== ����ʾ�����⣬���Ҫɾ�����ɵ�.a��.so����Ҫ��clean�����ɾ�����ļ�(��ģ�岻��.a��ƥ��)��
* Ĭ�ϱ��룺make
* ��ϸ���������Ϣ��make V=1  (VΪ��д)
* ���԰汾��make debug=y
* �ǵ��԰汾��make debug=n
* �������汾��make CROSS_COMPILE=arm-linux-

ע������
=======================
�ں�Makefile��Ҫ�ֶ�ָ������������ļ�(.o��ʽ)��ʹ��ͨ���ƥ���޷����롣

��Ȩ
=======================
��Ȩ���С�<br>
��Ŀ¼�����ļ����������κ�Ŀ�ġ�����(����ѧϰ�о�������)����ӭ���ʹ�ã��κ�����ɷ��������ߡ�

����
=======================
˼�ù����� ���(Late Lee at li@latelee.org) <br>

[��˼�ù�����](http://www.latelee.org) ��ӭ�������ߣ�

���·�������: <br>
2020.11.01 <br>
