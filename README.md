## 原始项目

[one-api](https://github.com/songquanpeng/one-api)

## 部署
```
docker run --name one-api \
    -d --restart always  \
    -p 3001:3000  \
    -e TZ=Asia/Shanghai  \
    -v /opt/one-api:/data  \
    durianice/one-api
```