## Linux常用命令行 [网站](https://www.yahboom.com/build.html?id=2625&cid=308 "跳转")
1、查看操作系统版本  
```Bash
cat /proc/version #Bash
```
2、查看主板版本  
```Bash
cat /proc/cpuinfo #Bash
```
3、查看SD存储卡剩余空间  
```Bash
df -h #Bash
```
4、查看ip地址  
```Bash
ifconfig #Bash
```
5、压缩  
```Bash
tar –zcvf  filename.tar.gz dirname #Bash
```
6、解压  
```Bash
tar –zxvf filename.tar.gz #Bash
```
7、apt(Advanced Package Tool)高级软件工具用法  
```Bash
sudo apt-get install xxx     #安装软件
```
```Bash
sudo apt-get update          #更新软件列表
```
```Bash  
sudo apt-get upgrade         #更新已安装软件
```
```Bash
sudo apt-get remove xxx      #删除软件
```
## Vim编辑器及其配置
Linux自带有nano与vi编辑器，但vi使用不方便，于是需要下载vim编辑器，vi的升级版。  
更新索引源：  
```Bash
sudo apt-get update #Bash
```
安装vim编辑器：  
```Bash
sudo apt-get install vim #Bash
```
