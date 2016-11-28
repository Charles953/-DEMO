# WeChat-demo
- 后台管理系统
- 微信订阅号开发
- 项目技术：nodeJS、Express框架、 MySQL、 Bootstrap（后台）、MUI（移动站点）

## 数据库表
### userInfo
- uid:{type:'serial',key:true},
- uname:String,
- upwd:String,
- ustatus:Number

### videoInfo
- vid:{type:'serial',key:true},
- vtitle:String,
- vsortno:Number,
- vvideid:String,
- vsummary:String,
- vremark:String,
- vimg:String

## 后台管理系统
- 使用Bootstrap框架搭建后台页面
- 包含src（开发版），dist（发布版）
- 已使用gulp压缩文件，代码

#### userInfo
- 登录
- 暂不支持注册，管理编辑

#### videoInfo
- 添加、删除、编辑（里面使用了ueditor富文本编辑器）、搜索

## 系统API
- 为前台提供获取视频列表，视频详情的API

## 移动站点
- 基于MUI框架进行搭建的移动站点
- 页面： 视频列表，视频详情

##  微信订阅号运营者服务器
### 关注功能
- 文本回复，并推荐首页，已达到推广的效果

### 关键字自动回复
- 图文信息回复，并发送视频详情

### 注意
- 如需要使用该项目，请自行申请个人订阅号
- 本项目URL提供是使用第三方免费服务器站点

## 微信服务
- 发送关键字信息，回复相应的视频信息
