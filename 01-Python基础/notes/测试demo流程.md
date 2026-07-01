在D盘新建一个my-test测试文件夹，在此文件夹中新建一个my_bank.py文件
在my-test.py文件中编写一个模拟银行业务测试代码demo，保存文件
点击“我的电脑”进入文件所在的文件夹属的ip栏输入cmd



进入命令页面，输入命令：pytest -v --alluredir=./report
  -v：显示详细的测试用例名称（你会看到那 3 个 passed）。
  --alluredir=./report：指定把生成的报告数据放在当前目录的 report文件夹里。
生成网页版报告：npx allure serve report
