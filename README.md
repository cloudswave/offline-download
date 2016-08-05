# offline-download
docker版离线下载服务器
### 安装
```
sudo docker run -d -p 80:80 -p 6800:6800 -v /tmp/modata/comic:/var/www/html/comic index.tenxcloud.com/ethanzhu/offline-download
```
###Dockerfile
```
FROM easychen/modo.moe
```
### docker加速器
```
curl https://coding.net/u/ethanzhu/p/shell/git/raw/master/docker-new-setmirror.sh | sh
```
