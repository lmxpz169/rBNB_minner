# rBNB_minner
| 全自动mint rBNB脚本，一键后台运行，智能托管

## 申明（写在最前面）
1. 原创仓库：https://github.com/yuanluoyue/rbnb-mine

## 提示
1. 运行前，请自行搭建好nodejs环境

## 操作步骤
### 钱包配置
* wallets.csv填写钱包地址，无需私钥、记助词，支持多个钱包地址

### 一键运行
| 第一次运行，建议用这个（包含环境搭建）
#### Mac电脑\Liunx系统
* 输入以下指令：  
./run.sh

#### Windows电脑 
* 输入以下指令：  
.\run.ps1

### 直接运行
* npm run start

### 停止脚本
* pm2 stop all
* pm2 kill

### 查看日志
* 登录https://pm2.io/
* 按照提示进行登录
* 点击“SHOW LOGS”即可