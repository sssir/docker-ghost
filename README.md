# docker-ghost
修改自：https://github.com/jwasham/docker-ghost-template.git

## 版本
Docker: 17.06.0
Nginx: 1.8.1
Ghost: 1.5.2

## 使用
* 将SSL证书放到`nginx/volumes/conf.d/ssl`
* 根据你自己的需求修改`nginx/volumes/conf.d/ghost.conf`(将`your-domain-name`替换为你的域名)
* `docker-compose up -d`启动服务
* Ghost的数据将会保存在`Ghost/volumes/content`中
