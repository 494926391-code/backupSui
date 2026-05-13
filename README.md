----------本地文件安装sui面板-------------

1、上传sui压缩文件到root目录
mkdir -p /usr/local/s-ui && tar -xzvf /root/s-ui.tar.gz -C /

2、启动服务
chmod +x /usr/local/s-ui/sui && nohup /usr/local/s-ui/sui > /dev/null 2>&1 &

3、登录成功后修改账号密码
http://ip地址:2095/app/
账号      U2FsdGVkX1/8KE
密码      1nr6ogIP/4ztdFbQS3U6FFbKRrNPE=
