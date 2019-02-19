# learn docker-compose
1. build image 
```docker build -t {imageName} .```
2. edit docker-compose.yml
3. if on Local system environment you can add 
```zulin_local.bmmyou.com 127.0.0.1```
in you system hosts , otherwise edit ./nginx/zulin.conf change server_name 
4. run 
```docker-compose up -d```
5. now you can put file in this project 
