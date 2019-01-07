# springboot war linux 控制脚本

## 修改配置文件
修改app.config, 配置如下配置名

#应用名称
>app_name="broadcast"

#应用目录,war文件存在路径
>app_home="/home/zltel/broadcast/"

#启动app文件名
>app_file_name="broadcast*.war"

## 启动
```Linux
./app.service.sh start 
```

## 停止
```Linux
./app.service.sh stop 
```
## status
```Linux
./app.service.sh status 
```
