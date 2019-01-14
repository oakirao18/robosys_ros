## robosys_ros

ROSを使ったウェブにデータを飛ばすプログラム及び、パブリッシャ、サブスクライバによるデータ通信を行う

## Demo



## Description

ROSを使いweb上に白い大きな文字を送ることができる。  
また、パブリッシャ、サブスクライバにより変動する数字を送ることができる。  
使用したもの  
・ノートPC(Windows10)  
・VirtualBox  
　Ubuntu16.04  
・ROS Kinetic  

## Install

```
git clone https://github.com/oakirao18/robosys_ros.git
```

## Usage
#### Webに送るプログラム
ターミナルに入力する
```
roslunch mypkg mypkg.lunch
```
ブラウザで入力する
```
http://{IPアドレス}:8000
```
#### パブリッシャ―、サブスクライバによる通信の確認
各コマンド新しいターミナルで入力する。
```
roscore
rosrun mypkg count.py
rosrun mypkg twice.py
```

## Licence
[GPL](https://www.gnu.org/licenses/gpl-3.0.ja.html)
