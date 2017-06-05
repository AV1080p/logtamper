# logtamper
python修改linux日志

# 使用

躲避管理员w查看

python logtamper.py -m 1 -u re4lity -i 192.168.0.188

清除指定ip的登录日志

python logtamper.py -m 2 -u re4lity -i 192.168.0.188

修改上次登录时间地点

python logtamper.py -m 3 -u re4lity -i 192.168.0.188 -t tty1 -d 2014:05:28:10:11:12
