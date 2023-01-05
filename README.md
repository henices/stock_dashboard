
A fork of https://github.com/geeeeeeeek/stock_page

- 增加 Python3 支持
- 调整看板界面
- 规避新浪网的查询检查

```bash
while true; do python3 handle_csv.py ; sleep 60; done
```

![image](https://user-images.githubusercontent.com/929715/210698581-4c1f36c0-b69e-4df6-bef3-6147e3beb96c.png)

## 项目简介

Python开发的股市行情看板

原项目演示地址：[https://geeeeeeeek.github.io/stock_page/](https://geeeeeeeek.github.io/stock_page/)

近期股市又骚动起来，回忆起昔日炒股经历，历历在目，悲惨经历让人黯然神伤，去年共投入4000元入市，最后仅剩1000多，无奈闭关修炼，忘记股市，全身心投入代码世界，享受代码带来的乐趣。近日，当看到别人用 Python进行量化投资暴富的消息，顿时振奋，立刻学习起 Python数据分析之道，开发了一个股市行情看板，希望借Python之力，早日实现财务自由，达到人生巅峰。

## 项目依赖

依次安装下面的 Python 依赖即可正常运行。

```bash
pip install numpy
pip install bottle
pip install requests 
```

## 运行方式

`python handle_csv.py` 即可生成index.html

---

炒股不科学，亲人两行泪。
