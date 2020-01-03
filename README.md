# learn docker-compose
1. build image 
```docker build -t {imageName} .``` 
- 使用上面的指令创建镜像 ,镜像名建议使用 php7.2 
2. If the name created in the first step is php7.2, skip this step . edit docker-compose.yml , mainly modify the image name of line 20 
- 如果第一步创建的名字为php7.2,跳过这一步. 修改docker-compose.yml文件 , 主要修改第20行的image名
3. Confirm that local port 80 is not occupied. 
- 确认本地端口80没有占用 
4. run 
```docker-compose up -d```
If it fails, confirm port 80,  use ```docker-compose down ``` to close the service and restart docker. 
-使用 ```docker-compose up -d``` 启动服务， 如果失败,确认80端口, 使用 ```docker-compose down ``` 指令关闭docker-compose服务 排查错误，确认无误后使用之前的指令启动服务。

