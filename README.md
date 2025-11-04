# 学校防疫物资管理平台

## 前言

随着新冠疫情的不断发展，学校对防疫物资的管理变得尤为重要。为了提高防疫物资的管理效率，我们开发了一款学校防疫物资管理平台。本项目基于Java语言和Spring Boot框架，结合前端技术JS、Vue和css3，实现了物资信息的录入、查询、统计等功能。

## 内容介绍

学校防疫物资管理平台主要包括以下模块：

1. 用户登录模块：实现用户的注册、登录和权限管理。
2. 物资信息模块：实现防疫物资的录入、查询、修改和删除。
3. 物资统计模块：根据物资类别和时间段进行数据统计和展示。
4. 系统管理模块：实现对用户、角色和权限的管理。

通过以上模块的协同工作，学校防疫物资管理平台可以高效地实现对防疫物资的全方位管理。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是物资信息模块中查询物资信息的核心代码：

```java
@RequestMapping("/queryMaterial")
public ResponseEntity<List<Material>> queryMaterial(@RequestParam("keyword") String keyword) {
    List<Material> materials = materialService.queryMaterial(keyword);
    return ResponseEntity.ok(materials);
}
```

该代码定义了一个RESTful API，接收前端传来的查询关键字，调用materialService的queryMaterial方法查询相关物资信息，并将查询结果返回给前端。

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/317590/24/24472/179684/689e1295F92be71ed/f875401ba1c35ac4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/313933/27/26980/40442/689f2e83F6ec7a0fc/4fcd92f343ee19b8.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327680/11/4999/130099/689f2e83Fb7b54ea8/f550246d5c581998.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/318243/27/25147/55603/689f2e84Ff613ef55/d2ecbc563692ed04.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/324233/8/5012/28055/689f2e84Fcebb6900/8b8c1e3e5be727d5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/294511/38/19031/46805/689f2e84Ff786f36d/af7bc67f9cb55307.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/321367/15/25536/33850/689f2e85F44b9e36e/db700a86e3cc93c5.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325069/22/4986/95764/689f2e85F60980d28/678451585735e857.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/317475/26/25322/30098/689f2e86F113c2fed/ca3a5fc93cf684bb.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326547/8/4899/45458/689f2e86F5045605f/cf96688a9846ff7c.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
