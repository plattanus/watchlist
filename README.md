# watchlist

尊重原著所有：https://github.com/helloflask

运行指导：

1. 进入[FlaskImplementation](https://github.com/plattanus/FlaskImplementation)目录
2. 删除env和data.db文件
3. 创建虚拟环境

   ```
   python3 -m venv env
   ```
4. 进入虚拟环境

   ```
   source ./env/bin/activate
   ```
5. 安装所有依赖

   ```
   pip install -r requirements.txt
   ```
6. 初始化数据库

   ```
   flask initdb
   ```
7. 创建管理员账户

   ```
   flask admin
   ```
8. 退出虚拟环境

   ```
   deactivate
   ```
9. 运行

   ```
   flask run
   ```


现在输入在浏览器中输入：http://127.0.0.1:5000 即可。
