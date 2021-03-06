> - [folio-install](https://github.com/folio-org/folio-install/tree/master/runbooks/single-server)  
> - [folio-ansible](https://github.com/folio-org/folio-ansible)
> - [vagrant](https://app.vagrantup.com/folio)

FOLIO提供基于vargrant的单节点部署环境，可于https://app.vagrantup.com/folio 下查看folio相关的版本信息，在Ubuntu上以vargrant方式部署需要参照以下步骤： 

1. 安装 VirtualBox  
```
sudo apt-get install virtualbox
```

2. 安装vargrant
```
sudo apt-get install vagrant
```

3. 创建vagrantfile  
```
vagrant init folio/Q1-2019
```  
![GitHub](https://github.com/x19990416/macrossx-folio-knowledge-map/blob/master/FOLIO%E5%BF%AB%E9%80%9F%E5%85%A5%E9%97%A8/%E5%9B%BE%E7%89%87.png "vargrant_1")

4. 运行vagrant
```
vagrant up
```
vagran会自动下载 folio镜像

![GitHub](https://github.com/x19990416/macrossx-folio-knowledge-map/blob/master/FOLIO%E5%BF%AB%E9%80%9F%E5%85%A5%E9%97%A8/images/vagrant_2.png "vargrant_2")
![GitHub](https://github.com/x19990416/macrossx-folio-knowledge-map/blob/master/FOLIO%E5%BF%AB%E9%80%9F%E5%85%A5%E9%97%A8/images/vagrant_3.png "vargrant_3")

运行完毕在地址栏中输入
```
http://127.0.0.1:3000
```
可看到FOLIO的登录界面
