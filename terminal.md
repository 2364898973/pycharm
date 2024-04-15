以安装pymysql为例，输入以下命令回车即可使用镜像安装：

```
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pymysql
```

终端输入以下命令，修改pycharm的默认设置，之后pip install安装库默认使用国内镜像：

```
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
