# 启动

切片用于查看视频分析

```Shell
https://bot.sannysoft.com/
```

# webgl 检查

```Shell
            const getParameter = WebGLRenderingContext.getParameter;
            WebGLRenderingContext.prototype.getParameter = function(parameter) {
              if (parameter === 37445) {
                return 'Intel Open Source Technology Center';
              }
              if (parameter === 37446) {
                return 'Mesa DRI Intel(R) Ivybridge Mobile ';
              }
            
              return getParameter(parameter);
            };
```

# 启动

```Shell
dvr-scan -i video.mp4 -r
```