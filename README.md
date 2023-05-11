# H3C防火墙提取安全策略，对象组内容到表格 

1. 编写三个`textfsm`模板文件处理以下命令的回显内容

   ```
   # 查看安全策略
   dis security-policy ip
   # 查看地址对象组
   dis object-group ip address 
   # 查看服务对象组
   dis object-group service 
   ```

2. 使用textfsm模板对回显内容进行处理然后写入表格
