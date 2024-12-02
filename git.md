# 设置代理：

```shell
//http || https
git config --global http.proxy 127.0.0.1:10809
git config --global https.proxy 127.0.0.1:10809

//sock5代理
git config --global http.proxy socks5 127.0.0.1:10808
git config --global https.proxy socks5 127.0.0.1:10808
```
# 针对域名设置代理
```shell 
git config --global http.https://github.com.proxy http://127.0.0.1:10809
```

# 查看代理：

```shell 
git config --global --get http.proxy
git config --global --get https.proxy
```

# 取消代理：

```shell 
git config --global --unset http.proxy
git config --global --unset https.proxy
```
# 查看git的设置
```shell 
git config --global --list
```
# 全局修改
```shell 
git config --global user.name "Tony"
git config --global user.email "abc@qq.com"
```
# 局部修改

```shell 
git config user.name "Tony"
git config user.email "abc@qq.com"
```
