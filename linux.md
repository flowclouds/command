# 1.客户端生成公私钥

```shell
ssh-keygen
```

# 2.上传公钥到服务器

```shell
ssh-copy-id -i ~/.ssh/id_rsa.pub root@192.168.235.22
ssh-copy-id -i root@192.168.235.22
```
