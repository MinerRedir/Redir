# Redir
一键支持鱼池、蚂蚁、E池、欧意、币印5大矿池中的ETH、ETC、BTC<br>
有问题进电报群:https://t.me/+JsuIsFeLujsyOTRl<br>
# 步骤
## 1 先购买服务器
   腾讯云: https://curl.qcloud.com/OVGoothE <br>
   其他服务也可以 <br>
## 2 注册
  以腾讯云为例，首先打开腾讯云购买链接 注册登录（需要实名认证才能买）<br>
  ![image](https://user-images.githubusercontent.com/96757460/147722914-bd0e6a33-d00f-45a1-a9ca-2bbe89390202.png)<br>
  ![image](https://user-images.githubusercontent.com/96757460/147722929-3d55e767-9212-467d-ab76-7165fdb57007.png)<br>
  选择香港的延迟最低，不用一次买一年，一个月一个月续费就可以了。<br>
  后买成功之后进入控制台点击登录。<br>
  ![image](https://user-images.githubusercontent.com/96757460/147722957-521b2f30-63d7-4303-9c49-04f19795277b.png)<br>
  登录成功之后是这个样子<br>
  ![image](https://user-images.githubusercontent.com/96757460/147722969-38654d3a-6392-4f03-842a-106fb7cc62e9.png)<br>
## 3 输入命令
以下命令如果卡住，一直按回车键<br>
```Bash
  1、sudo apt update
  2、sudo apt install openjdk-17-jre-headless
  3、sudo apt install git
  4、git clone https://github.com/MinerRedir/Redir.git 
  5、cd Redir
  6、java Redir 
```
 ## 3 打开防火墙
   进入防火墙<br>
  ![image](https://user-images.githubusercontent.com/96757460/147723503-adc0ec04-8e91-4eee-93f7-8f17ae66e13e.png)<br>
  ![image](https://user-images.githubusercontent.com/96757460/147723624-e651f982-f77f-4d92-abad-10ec39cc5b3e.png)<br>
  ![image](https://user-images.githubusercontent.com/96757460/147723639-0ec97587-9a85-4eed-aeb9-33a6bb351c68.png)<br>
  到此就设置成功了。<br>

  ## 4 使用ip
  ![image](https://user-images.githubusercontent.com/96757460/147723678-199f8ece-15c4-44f7-86d3-5a588b12cd51.png)<br>
  查看自己服务器的ip，比如是1.1.1.1,那么你的中转是：<br>
  ```Bash
  鱼池ETH
  1.1.1.1:6688
  鱼池ETC:
  1.1.1.1:8119
  鱼池BTC:
  1.1.1.1:4433

  E池ETH
  1.1.1.1:14444
  E池ETC
  1.1.1.1:4445

  殴意ETH
  1.1.1.1:4336

  蚂蚁ETH
  1.1.1.1:8008
  蚂蚁ETC
  1.1.1.1:4443
  蚂蚁BTC
  1.1.1.1:4433

  币印ETH
  1.1.1.1:1883
  币印ETC
  1.1.1.1:7000
```
注意要替换成自己的ip，端口不变；

## 5 修改挖矿软件ip
 1、轻松矿工添加矿池<br>
 ![image](https://user-images.githubusercontent.com/96757460/147724006-e64e7296-1689-46b1-baa5-f5ee9467dec4.png)<br>
 2、开源矿工<br>
![image](https://user-images.githubusercontent.com/96757460/147724066-2dfb0193-af8c-4bf4-80b2-82d29e5b81d8.png)

