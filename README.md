# WeChat-demo
一个使用NodeJS，express框架+MySQL开发微信订阅号的小项目
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
### 包含src（开发版），dist（发布版）
- 已使用gulp压缩文件，代码

#### userInfo
暂时只做了登录功能
#### videoInfo
添加、删除、编辑（里面使用了ueditor富文本编辑器）

