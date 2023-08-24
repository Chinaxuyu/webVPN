# webVPN


# 安装必要的库
sudo yum -y install wget gcc gcc-c++ autoconf automake make

# 安装 VPN 脚本 ss.sh:
yum install python3
wget –no-check-certificate -O ss.sh https://raw.githubusercontent.com/Chinaxuyu/webVPN/main/ss.sh
#执行脚本

# 执行脚本
sh ss.sh
