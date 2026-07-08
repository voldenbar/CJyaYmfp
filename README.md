# 前言

大家好，今天我要分享的是一个基于Java和Spring Boot的社区医疗综合服务项目。这是一个适用于毕业设计的实战项目，其中包含详细的源码、文档报告和代码讲解。本项目致力于为中山社区居民提供便捷、高效的医疗服务。

# 内容介绍

本项目是一个集患者管理、预约挂号、就诊记录、药品管理等模块于一体的社区医疗综合服务平台。通过这个平台，患者可以轻松预约医生、查询就诊记录、购买药品等；医生可以方便地管理患者信息、查看预约情况、记录就诊历史等。此外，我们还提供了后台管理功能，方便医疗机构进行系统维护和数据分析。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、css3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven: apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下是本项目中的一个核心代码片段，展示了如何使用Spring Boot整合MyBatis实现患者信息的查询：

```java
@RestController
@RequestMapping("/patient")
public class PatientController {

    @Autowired
    private PatientService patientService;

    @GetMapping("/list")
    public List<Patient> listPatients() {
        return patientService.listPatients();
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/291580/13/25654/219351/689de946Fa2685db9/3cda4291d3356566.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/306163/17/23129/60370/689de927Fe0130d65/ab5761ec653fe30a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/328331/1/4583/181580/689de929F6973e034/0cc2a3c14fc16d05.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/315038/28/26311/36929/689de929Fcd15705f/0953cda6581a5348.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/315836/18/26242/36510/689de92bF57e3a294/94262c5a58dfdb2b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320740/10/25141/52795/689de92bF46382b27/d803404640b824e8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328576/27/4564/33672/689de92cF72b874d1/90b34ac3bc1a7fa5.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325373/1/4550/43127/689de92cFbc83fc53/b6bd79c82a670b6e.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/310003/13/26269/40198/689de92dF66793df8/36ab70fe1452845c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/296157/32/13817/181837/689de92dF26e452e8/c68f5ba70f879c5d.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
