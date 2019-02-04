# Linux-Learn-notes
## 安装typora——————markdown编辑器
Ubuntu安装方法在官网有明确指导，这里重点说明Linux mint下的安装：
```
# add Typora's repository
echo -e "\ndeb https://typora.io/linux ./" | sudo tee -a /etc/apt/sources.list
sudo apt-get update

# install typora
sudo apt-get install typora
```
