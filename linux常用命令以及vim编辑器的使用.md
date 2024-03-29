## Linux常用命令行 [网站](https://www.yahboom.com/build.html?id=2625&cid=308 "跳转")
1、查看操作系统版本  
cat /proc/version  
  
2、查看主板版本  
cat /proc/cpuinfo  
  
3、查看SD存储卡剩余空间  
df -h  
  
4、查看ip地址  
ifconfig  
  
5、压缩  
tar –zcvf  filename.tar.gz dirname  
  
6、解压  
tar –zxvf filename.tar.gz  
  
7、apt(Advanced Package Tool)高级软件工具用法  
sudo apt-get install xxx     安装软件。  
sudo apt-get update          更新软件列表。  
sudo apt-get upgrade         更新已安装软件。  
sudo apt-get remove xxx      删除软件。  
## Vim编辑器及其配置
  Linux自带有nano与vi编辑器，但vi使用不方便，于是需要下载vim编辑器，vi的升级版。  
  更新索引源：  
  sudo apt-get update  
  安装vim编辑器：  
  sudo apt-get install vim
