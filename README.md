# 青龙面板小工具 适用于2.2面板

## 修复远程扫码问题 支持AMD64和ARM64架构

## 配套前端地址
https://github.com/Zy143L/JDC_WEB

## 配套青龙2.2-066 不升级版本
https://hub.docker.com/r/limoe/qinglong

## 资源静态编译 修正部分缺依赖的问题 群晖 N1 玩客云 Docker已测试支持
![image](https://user-images.githubusercontent.com/21352718/123640178-7c0c5400-d853-11eb-9c1c-625a54c4d7ff.png)
![image](https://user-images.githubusercontent.com/21352718/123640300-9b0ae600-d853-11eb-8c35-eb89f7defc5e.png)
![image](https://user-images.githubusercontent.com/21352718/123640624-f1782480-d853-11eb-81d3-b247e9ca9385.png)
![image](https://user-images.githubusercontent.com/21352718/123640997-55025200-d854-11eb-81e8-a3c30633cde0.png)


## Docker无法使用的 去docker下执行
```21
apk add libc6-compat
```

### 使用方法 不再赘述 会用的都会用 

```
nohup ./JDC  1>/dev/null 2>&1 & #AMD64
```

```
nohup ./JDC_arm64  1>/dev/null 2>&1 & #ARM64
```

## 截止 2021年6月28日11:41:40 测试正常 

![image](https://user-images.githubusercontent.com/21352718/123577157-ded6fe80-d805-11eb-80fd-36f0dea30d24.png)

## 说明
本程序仅供交流学习使用，请勿使用本程序进行商业行为。

您应该在下载后的24小时内从您的计算机中删除本程序。

由使用本程序所产生的一切责任自负。

