升级OpenSSH,OpenSSL

本脚本测试通过Centos6.5—Centos6.9, Centos6.8出现编译失败时需要安装pam-devel扩展

Pam-devel安装步骤
```
wget wget http://mirror.centos.org/centos/6/os/x86_64/Packages/pam-devel-1.1.1-24.el6.x86_64.rpm
yum -y install pam-devel-1.1.1-24.el6.x86_64.rpm
```
