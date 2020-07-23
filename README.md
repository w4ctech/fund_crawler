基于[天天基金网](http://fund.eastmoney.com)的爬虫,并自动发送相关邮件
# fund_crawler
使用方法  
1.测试环境为python3.7.6,自行安装python3  
2.requirements.txt 是所需第三方模块，执行 `pip install -r requirements.txt` 安装模块  
3.可在脚本内直接填写[账号](https://github.com/h7ml/fund_crawler/blob/master/main.py#L20) [密码](https://github.com/h7ml/fund_crawler/blob/master/main.py#L21)  
4.Python 和需要模块都装好了直接在目录 cmd 运行所要运行的脚本。  

# Github Actions说明
## 一、Fork此仓库
## 二、设置账号密码
1 添加名为**emailUser**、**emailPassword**的变量  
2 值分别为**账号**、**密码**  
3 示例：**emailUser:w3ctech@qq.com**，**emailPassword:zfy66666**

## 三、启用Action
1 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
2 修改任意文件后提交一次  

## 四、查看运行结果
Actions > fund_crawler > build  

此后，将会在每天9:40,12:30,16:40
若有需求，可以在[.github/workflows/run.yml]中自行修改

## 五、鸣谢
[傲天](https://www.allsrc.cn/)
