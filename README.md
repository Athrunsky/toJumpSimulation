
跳一跳

## Instal

安装 [Node.js](https://nodejs.org/en/)

``git clone https://github.com/Athrunsky/toJumpSimulation.git

```shell
# 安装依赖
npm install

# 开启服务器，端口为4000，可通过config.js修改
npm start
```

## 使用方法

- 1.打开安卓手机的usb调试模式并授权连接的电脑
- 2.打开微信跳一跳，并点击开始
- 3.开启服务器，如上
- 4.点击开始，先点击小人底部适当位置，然后再点想要跳的箱子的位置即可完成，结束之后可点击开始可重新开始

## 开发环境是8.9.3。因为用到了Await/sync特效，低于node7的会报错，请使用gnvm调整
## 每两次点击会抓取一次截图反馈，可根据截图进行调整
## 目前针对720p和1080p显示设备优化，如有其他分辨率可能会出现两点不准的问题