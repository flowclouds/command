# 1.客户端生成公私钥

```shell
ssh-keygen
```

# 2.上传公钥到服务器

```shell
ssh-copy-id -i ~/.ssh/id_rsa.pub root@192.168.235.22
ssh-copy-id -i -p51002 root@172.30.21.139
```

# 3.从远程复制到本地

```shell
scp -P51002 -r root@103.74.121.246:/www/wwwroot/jenkins_data /www/wwwroot/jenkins_data
scp -r www.runoob.com:/home/root/others/ /home/space/music/
```

# 4.从本地复制到远程

```shell
scp local_file remote_username@remote_ip:remote_folder 
```