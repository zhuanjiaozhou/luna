#           // Luna //

Luna 是Jumpserver项目的web terminal子项目, 用户登陆 Luna可以获取拥有权限
资产列表, 登录资产,并记录日志等

### Quick start

```
                                                                                                                      $ brew install $(cat mac_requirements.txt)
$ pip install --user -r requirements.py -i https://pypi.douban.com/simple

$ export JUMPSERVER_ENDPOINT='http://a-jumpserver-url:port'
  # 或修改配置文件设置 JUMPSERVER_ENDPOINT 
  
$ python run_server.py
```

如果不想和Jumpserver联调,修改 run_server.py
```
# 注释掉
# app.bootstrap()
```

