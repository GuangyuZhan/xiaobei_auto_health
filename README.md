<h1 align="center">小北打卡助手</h1>

~~导员再也不用担心我的北温打~~

***低调使用！ 出事项目作者不负任何责任！***

# 使用方法

## 1. fork 本项目
**在这之前，你可能得先注册一个 github 账号**



![](./assets/fork.png)

## 2. 填写你的用户名（身份证号）和密码（身份证号后六位）添加到仓库的 Secrets 中

![](./assets/secrets.gif)

***请不要无脑照着图抄！！！！！！ 记得替换你身份证号码进去！！！！！！！！！！！！***

请一定要保持`标题（Name）`不变！！！！！！！！

身份证号码的 `Name` 是 `IDCODE`！！！！！

密码的`Name`是 `PASSWORD`！！！！！

***这里添加密码不会外泄你的信息！！！！！！！***

***请放心添加！！！！！！***


## 3. 开启 actions

![](./assets/open_actions.gif)

## 4. 自己提交一次 push

![](./assets/push.gif)

## 5. 完成啦\~\~\~\~

***脚本会在每天早上 10 点钟自动为你北温打，导员再也不用担心我的北温打\~\~\~***



---



# 第二种使用方法

首先将本项目 clone 或者下载到本地

然后在 config.py 中写入你的身份证号和密码（默认为身份证号后六位）

注意不要去掉双引号

```python
username = "100000199801020022"
password = "262428"

```

在完成后，它应该像上面这样

# 运行

```bash
pip3 install requests
# 安装依赖
python3 main.py
# 执行
```

 

# //TODO

准备支持微信推送



# 免责声明

这个项目是纯粹为了学术研究的目的而创建的。 
项目维护者不对软件的滥用、使用负任何责任。

