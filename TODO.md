### TODO List 待办事项

> 看起来很可怕，其实也没有这么恐怖啦→_→

> 不信可以看这个文件第一次 commit 打了勾的，都是我一周内做出来的。

#### 界面（不含播放器）

- [x] 主界面 Drawer 布局
- [x] 主界面 - 主页布局 **（滑动交互不完美，仍需改善）**
- [ ] 主界面 - 正在关注 （需要在用户登录系统完成后）
- [ ] 主界面 - 探索
- [ ] 主界面 - 下载管理 （优先级低）
- [ ] 搜索界面 （设计说明：应由主界面的搜索按钮另外唤出一个 Activity 进行搜索）
- [ ] 设置界面
- [ ] 主界面 - 我的收藏夹
- [ ] 主界面 - 历史记录
- [x] 视频详情信息界面 **（Tags 解析还没有做好）**
- [ ] 视频评论界面
- [x] 其他用户信息界面
- [x] 正在关注的用户列表界面
- [ ] 专题详情信息界面
- [ ] Tag 分类界面
- [ ] 我的信息界面
- [ ] 登录界面（可能用 WebView 获取授权）

#### API 接口和模型

- [x] 基本框架和密钥生成
- [x] Index 首页
- [ ] Sp 专题信息 **（未完成关注/取消关注）**
- [x] Video 视频信息 （有 VideoItemInfo/VideoViewInfo 两种，后者信息更详情，注意区分）
- [x] Banner 黑魔法首页顶栏
- [x] Bangumi 最新番剧
- [x] UserInfo 用户信息
- [ ] Friend 朋友 **（未完成关注/悄悄关注/黑名单）**
- [ ] Favourite 收藏
- [ ] Comment 弹幕
- [ ] Feedback 评论
- [ ] Search 搜索
- [ ] Tags 标签
- [ ] History 历史记录
- [ ] 用户登录 Access Key 管理

#### 播放器

- [ ] 播放器基本界面
- [ ] 播放器解码与 View （预计使用 ijkplayer 或 vitamio）
- [ ] 弹幕引擎（使用 [烈焰弹幕使](https://github.com/bilibili/DanmakuFlameMaster)）
- [ ] 弹幕发送/屏蔽
- [ ] 一些播放器的基本功能

#### 实用功能

- [ ] 用户登录/注销
- [ ] 通知功能 （优先级低）
- [ ] 视频下载功能
- [x] 内置浏览器
- [ ] 检查更新

#### Android Wear （优先级超级低）

- [ ] 通知/番剧更新动态
- [ ] 番剧列表（主界面）