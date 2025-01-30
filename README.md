# minionlab_bot
注册RF: https://app.minionlab.ai/?referralCode=ZkPbNqdn

chrome插件：https://chromewebstore.google.com/detail/minionlab/fgamijdhamopilihagheoalbifagafka

## 1.0版本教程

### 1.1 配置说明
#### 1.1.1 config 目录是脚本配置

config---userids.txt 是用户、密码、推荐码存储文件，用于注册，获取用户id是用到

config---token.txt 是存储用户id的文件，可以生成或者手工抓取。挂机时候用到

config---proxy.txt 是代理文件，用于注册和挂机使用

config---credentials.txt 是序列号文件，用于认证脚本合法性使用。由系统生成


#### 1.1.2 log 目录是脚本日志

log---error_log.txt 是用于记录脚本重大错误时候使用！由系统自动生成

### 1.2 如何配置？

1、``userids.txt``用户和密码文件格式
```txt
Email:passwd:rfcode #按照这个格式输入，这行可以删除！
dandan@gmuali.com:dandan:dandan
```


2、``token.txt``用户id格式由脚本自动生成

3、手动抓取，打开https://app.minionlab.ai/页面，登录，开启开发者模式(F12)->网络->myInfo的地址点击->响应->找到UUID

4、``proxy.txt``代理文件格式
支持http和socks5协议的代理，一行一个

### 1.3 如何运行？
#### 1.3.1 Mac
```bash
cd 你的目录路径
chmod +x Minionlab_Mac.bin
./Minionlab_Mac.bin
```
#### 1.3.2 Linux
```bash
cd 你的目录路径
chmod +x Minionlab_Linux.bin
./Minionlab_Linux.bin
```
#### 1.3.3 Win
建议在win11下运行，兼容win10版本（会有乱码日志）

1、无日志运行，双击即可

2、带日志运行，cmd到项目下，运行：``.\Minionlab_Win.exe``





