# 0. 라즈베이파이 업데이트
```
sudo apt update
sudo apt upgrade
```
# 1. Repository의 GPG key를 더하기
```
wget -qO- https://repos.influxdata.com/influxdb.key | sudo apt-key add -
```
# 2. Repository를 더하기
```
echo "deb https://repos.influxdata.com/debian stretch stable" | sudo tee /etc/apt/sources.list.d/influxdb.list
```
