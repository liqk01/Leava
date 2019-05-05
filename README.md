<p align="center">
  <a href="https://github.com/joey66666/Leava">
    <img src="https://github.com/joey66666/Leava/blob/master/docs/logo/Leava.png"  width="152">
  </a>
  <h3 align="center">Leava</h3>
  <p align="center">
    <a href="https://github.com/joey66666/Leava/blob/master/LICENSE"><img src="https://img.shields.io/badge/license-Anti%20996-blue.svg?style=popout-square"></a>
    <a href="https://github.com/joey66666/Leava/blob/master/README_en.md"><img src="https://img.shields.io/badge/doc-English-red.svg?style=popout-square"></a>
    <a href="http://hits.dwyl.io/joey66666/Leava" alt="hit count"><img src="http://hits.dwyl.io/joey66666/Leava.svg" /></a> 
  </p>
  <p align="center">
    基于Flask+MySQL的在线请假微信小程序<br>
  </p>
</p>

# Leava

**仓库路径声明**

- [Images&UI](https://github.com/joey66666/Leava/tree/master/Images%26UI/UI%E5%9B%BEpng) 为设计图和icon，logo

- [frontend](https://github.com/joey66666/Leava/tree/master/frontend) 为微信小程序源代码

- [backend](https://github.com/joey66666/Leava/tree/master/backend) 为后端源代码

- [docs](https://github.com/joey66666/Leava/tree/master/docs) 为数据库设计文档，调试记录，流程图和真机调试截图

**如何启动**

- 在本地建立数据库，详见[数据库设计](https://github.com/joey66666/Leava/blob/master/docs/%E5%B0%8F%E7%A8%8B%E5%BA%8F%E6%95%B0%E6%8D%AE%E5%BA%93%E8%AE%BE%E8%AE%A1.md)
- 在[RESTful_backend](https://github.com/joey66666/Leava/tree/master/backend/RESTful_backend.py)中配置数据库连接(Line: 32 & 368) 并启动
- 在微信web开发者工具中新建小程序项目，选择空目录创建并复制粘贴 [frontend](https://github.com/joey66666/Leava/tree/master/frontend) 中文件
- 开始使用

**用户需求**：

- 学生提交请假请求，查看自己的请假详情和请假是否被批准等情况

- 辅导员管理学生的请假请求，查看学生请假记录

- 任课老师接查看学生的请假请求和是否被批准情况

### 用户身份

1. 学生，用户名为学号， 长度9位
2. 辅导员，用户名为工号， 长度6位
3. 任课教师，用户名为工号， 长度6位

### 技术栈

前端：微信小程序

后端：Flask+微信云开发（上传图片功能使用云开发，其他功能使用Flask）

数据库：MySQL

***

## 功能流程

![功能流程](https://github.com/joey66666/Leava/blob/master/docs/%E8%AF%B7%E5%81%87%E7%B3%BB%E7%BB%9F%E6%B5%81%E7%A8%8B%E5%8A%9F%E8%83%BD%E5%9B%BE.jpg)

***

## 架构设计

![ 架构设计](https://github.com/joey66666/Leava/blob/master/docs/%E8%AF%B7%E5%81%87%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1.jpg)

***

## 最终效果

![demo](https://github.com/joey66666/Leava/blob/master/docs/final_demo.jpg)

[More screen shots](https://github.com/joey66666/Leava/tree/master/docs/screenshot)


### 致谢

[Fuhaixu](https://github.com/Fuhaixu)、ZYN、[xuyongxiang](https://github.com/xuyongxiang134)
