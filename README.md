# openloop-in-ubuntu22
## OpenLoop脚本 我的邀请码olf905c9be

- 官方网站 [https://openloop.so/](https://openloop.so/)
- 官方推特 [@openloop_so](https://x.com/openloop_so)
## **性能要求**
- **建议**：1vcpu 0.5g 2Mbps
- **占用**：1vcpu下5%性能 20mb内存
## **要求**
- **ubuntu22**：不对其他系统保证支持，原则上主流linux都能跑
- **Python环境**：确保已安装python环境，未安装请看https://cn.linux-console.net/?p=20515，自行解决

## **开始部署**
1.克隆此仓库：
   ```bash
   git clone https://github.com/zhuochen0410/openloop-in-ubuntu22.git
   cd openloop-in-ubuntu22
   ```
这会让你下载本脚本资源，cd命令会让你进入openloop-in-ubuntu22文件夹

2.安装依赖：
   ```bash
   pip install -r requirements.txt
   ```
3.如果你使用finalshell，上一步的cd命令后直接会转到openloop-in-ubuntu22文件夹，找到并打开`accounts.txt`文件，填写邮件和密码
**需要使用代理则必须1账号对应1IP
4.填好后`python openloop-bot.py`或`python3 openloop-bot.py`

5.运行一次2选项，自动获取token
**集成了注册功能，未注册的邮箱会被自动注册，如果是未注册的账户建议再跑一次选项2确保获取token
6.继续运行1选项即可
