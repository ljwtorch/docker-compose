# redis cluster  

#### 简介  
redis集群，使用cluster模式。使用`bitnami`提供的镜像，版本为`6.2.6`。  

#### 注意事项  
- 替换ip地址  
使用前需要将`192.168.94.13`全部替换为自己的机器ip，为了除本机以外的机器可以正常访问，请**务必使用宿主主机的ip地址**。

> Windows可使用`ipconfig`指令查看本机地址，Linux或MacOS可以使用`ifconfig`指令查看本机地址。
部分Linux发型版如果没有`ifconfig`，也可以使用`ip addr`指令。  

- 修改认证密码  
默认配置的认证密码为`fake`，账号为空字符。使用前请按需修改。  

- 确认网络连通性  
请确保`6379`-`6384`以及`16379`-`16384`两个范围的端口均可访问。
