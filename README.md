# Game-trading-website

#### 介绍
毕设：基于Springboot的在线游戏道具商城的设计与实现

#### 软件架构
- Springboot+vue+MySQL

#### 部署系统必备
- JDK（1.8版本,并配置系统环境变量）
- MySQL（5.7版本）
- Navicat for MySQL（可视化）
- Maven（换阿里源，管理Jar包）
- Lombok插件（简化实体类）

#### 其它
- 数据库里的账号密码默认都是 123456，进行过加盐加密
- 管理员默认入口  localhost/admin
- 超级管理员账号密码：admin  admin

### 已有功能
  #### 登陆、注册、重置密码模块
  1. 登录：登录可以使用手机号或用户名进行登录
  2. 注册的时候会判断账号是否以及存在，用户名是否已存在。
     
     会判断手机号及邮箱的格式，但不会判断邮箱是否已使用过。
     
     发送短信验证时也会对手机号进行查重，验证码五分钟内有效。
  3. 重置密码时会验证手机号格式，判断是否存在该用户，  短信验证码五分钟有效。 

  #### 商品模块
  1. 发布商品
  2. 修改商品
  3. 商品详情界面
  4. 首页界面
  5. 商品列表界面
  6. 商品搜索界面

  #### 评论模块
  1. 查看商品下所有评论及回复
  2. 评论回复以及对应删除操作

  #### 个人中心
  1. 修改个人信息
  2. 修改密码
  3. 分页展示个人各类商品信息 已审核:1，待审核:3，违规:0，已完成:4
  4. 个人对商品的操作 删除:2  已完成:4
  5. 更换手机号

  #### 收藏模块
  1. 商品详情界面：收藏商品or取消收藏
  2. 收藏列表界面取消收藏
  3. 分页查看用户所有收藏内容
  4. 查看商品收藏状态

  #### 售出记录模块
  1. 用户设置商品为售出状态时存入售出记录
  2. 用户分页查看所有的售出记录
  3. 用户删除售出记录

  #### 聊天模块
  1.可以进行在线聊天

  #### 公告模块
  1. 发布公告
  2. 默认展示最新发布的前三条公告
  3. 公告详情的展示
  4. 修改公告及删除公告
  5. 删除公告

  #### 后台操作功能
  1. 管理员登录
  2. 查看用户列表
  3. 给予用户封号
  4. 管理员审核商品
  5. 管理员分页展示各类商品信息 全部，已审核:1，待审核:3，违规:0 完成:4
  6. 管理员对商品的操作 违规:0 通过审核:1

  #### 网站公告
  1. 管理员发布网站公告
  2. 管理员本人修改或删除公告
  3. 查看网站公告

  #### 通知模块
  1. 评论回复、商品审核、私信发送通知
  2. 设置为管理员或用户发送通知

  #### 部分图片
  1.登录界面
![1.jpg.png](https://i.loli.net/2021/08/16/i5sfUKF9ApewkTx.png)

  2.商城首页
![2.jpg.png](https://i.loli.net/2021/08/16/ZgRb3tm8d7nacx4.png)

  3.商品详情
![3.png](https://i.loli.net/2021/08/16/d5X7DWALxpjsKqS.png)

  4.个人中心
![4 _2_.png](https://i.loli.net/2021/08/16/G8ywxdteOIRDzqf.png)

  5.后台界面
![5.png](https://i.loli.net/2021/08/16/tQSv8RHG53PKInz.png)

