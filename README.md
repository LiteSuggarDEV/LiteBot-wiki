# LiteBot Wiki（For LiteBot V1.12 Full）

![lt](https://github.com/user-attachments/assets/cea6ea42-6c01-4e8f-8960-0cfffd301280)


## 开始
LiteBot是一个基于[Nonebot](https://nonebot.dev)开发的**公益免费**的QQ bot。是一款多功能的工具类型机器人，提供丰富的指令以增强群聊体验。它支持多种实用功能，从服务器状态查询到图像识别等，能够帮助用户更高效地互动和获取信息。  

## 主要功能  

### 群内独占指令  
- **/group**: 打开群聊功能菜单。  


### 主菜单功能指令  
- **/menu**: 显示主菜单。  
- **/info**: 获取系统信息。  
- **/QR `<text>`**: 生成二维码。  
- **/mc_java `<host:port>`**: 查询Java版Minecraft服务器状态。  
- **/mc_be `<host:port>`**: 查询基岩版Minecraft服务器状态。  
- **/web**: 打开Web功能菜单。  
- **/mcp**: 打开Minecraft玩家菜单。  
- **/fun**: 打开其他功能菜单。  
- **/news**: 获取更新日志。  
- **/chat `<msg>`**: 与Qwen聊天（不支持上下文）。  
- **/base64 `[encode|decode]` `<text>`**: 进行Base64编码或解码。  
- **/github `<账户>/<仓库>`**: 获取GitHub仓库信息。  
- **/other**: 打开异常功能菜单。  
- **/ocr `<图片/引用图片>`**: 进行图片识别。  

### 二级菜单及指令用法：
#### /group 群组管理菜单
- **/enable**: 在该群启用 LiteBot  
- **/disable**: 在该群禁用 LiteBot  
- **/recall**: 使用 LiteBot 身份撤回一条消息  
- **/welcome**: 切换是否启用成员变动提示  
- **/killnailong `<enable|disable>`**: 开启/关闭群内贝利亚安全卫士功能  
- **/msgsafe**: 违禁词/聊天检测   
  - 注意：违禁词列表将以 Base64 编码发送，请自行解码。  
  - 以下是**子选项说明**：
  - **system**: 使用系统词库  
  - **custom**: 使用自定义词库  
  - **mixed**: 使用系统 + 自定义词库  
  - **ai-judge**: 使用 AI 判断  
  - **ai-system**: 使用 AI 判断 + 系统词库  
  - **ai-custom**: 使用 AI 判断 + 自定义词库  
  - **ai-mixed**: 使用 AI 判断 + 系统词库 + 自定义词库  
  - **enable**: 启用功能  
  - **disable**: 禁用功能  
  - **add `<词>`**: 添加自定义违禁词  
  - **del `<词>`**: 移除自定义违禁词  
  - **list**: 列出违禁词（Base64 输出，自行解码）  

- **/config**: 展示群管功能配置（不展示 nailongkiller）  
- **/mute @sb. `<时间(分钟)>`**: 设置禁言  
- **/kick @sb.**: 踢出群聊  

#### **/mcp** MC玩家功能菜单
- **/mc-uuid** `<id>` :获取一个正版玩家的UUID
- **/mc-avatar** `<id>` :获取一个正版玩家的皮肤头部
- **/mc-skin** `<id>` :获取一个正版玩家的皮肤
- **/mc-body** `<id>` :获取一个正版玩家的皮肤渲染图

#### **/fun** 其他功能菜单
- **/yxh** `<主体>,<说法1>,<说法2>,<说法3>` :营销号音频生成器
- **/movie** `<文段>` :电影解说音频生成器
- **/die** ：趋势的小曲（
- **/surprise** :好 康 的
- **/night** :深夜福利（）
- **/round** :旋转两圈半

#### **/other** 异常菜单
此功能菜单**不固定**，如果有出现问题都会挪到这里来。

## 获取帮助  
加入我们的社区群：**1002495699**，与其他用户交流并获取更多支持。  

---  

如需了解更多信息，请随时使用相应的指令探索LiteBot的功能！
