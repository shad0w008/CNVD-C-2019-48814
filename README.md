# CNVD-C-2019-48814
WebLogic wls9-async反序列化远程命令执行漏洞


### 漏洞复现：

```
curl -i http://10.10.20.166:7001/_async/favicon.ico
```

![](./python.jpg)

![](./burpsuite.jpg)

###  CVE-2017-10271 No pactch

##### resever_shell
![](./reserve_shell.jpg)

![](./command.jpg)
![](./webshell.jpg)

