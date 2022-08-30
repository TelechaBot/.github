![cover](https://raw.githubusercontent.com/TelechaBot/TelechaBot/main/CaptchaCore/cover.png)
-----


<p align="center">
  <img alt="License" src="https://img.shields.io/badge/LICENSE-Mit-ff69b4">
  <img src="https://img.shields.io/badge/USE-python-green" alt="PYTHON" >
  <img src="https://img.shields.io/github/v/release/TelechaBot/TelechaBot?style=plastic" alt="V" >
  <a href="https://dun.mianbaoduo.com/@Sky0717"><img src="https://img.shields.io/badge/Become-sponsor-DB94A2" alt="SPONSOR"></a>
</p>

应当使用 Python 3.7 或更高版本

基于题目模型的生物验证

**快捷部署**
```
curl -LO https://raw.githubusercontent.com/TelechaBot/TelechaBot/main/setup.sh && sh setup.sh

cd TelechaBot

vim Captcha_exp.yaml 

# 填入你自己的token和信息，变更默认的验证Bot链接
```

**后台运行**

```shell
nohup python3 main.py > output.log 2>&1 &
```

**查看进程**

```
ps -aux|grep python3
```

[部署文档](https://github.com/TelechaBot/TelechaBot/blob/main/README.md)

[测试实例](https://t.me/SmartCapthaBot)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
