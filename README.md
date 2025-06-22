<img width="1246" alt="a6ca512cc7aa9ec219fd1f51922cb83" src="https://github.com/user-attachments/assets/095fa775-fcb3-4413-8ec1-32c7d1a4a5c9" />#  beauty_system - 美妆美饰巧搭平台 - 更多在微信 ： jackSinWu --在咸鱼：不知名选手java小鑫

美妆美饰巧搭平台是一个集 **穿搭推荐、妆容学习、搭配分享、互动交流** 于一体的个性化推荐平台，基于用户的外貌特征（如身材、肤色、风格）和使用场景，实现智能推荐与个性化服务，助力用户提升形象管理与美妆搭配能力。

<img width="1241" alt="1ab322aaf445f12a4ccacab824ed47b" src="https://github.com/user-attachments/assets/c7f93460-57ec-4bd0-8c9a-c1dd3ad40e8d" />
<img width="1244" alt="6ed58401178ea206770794a5ff1eca5" src="https://github.com/user-attachments/assets/61a91d91-c430-4e64-b675-966df15a2e10" />
<img width="1246" alt="a6ca512cc7aa9ec219fd1f51922cb83" src="https://github.com/user-attachments/assets/a37c375d-ead5-439e-ae25-b341669a49e5" />
<img width="1245" alt="984e1f7cd68be50e47c52b440363023" src="https://github.com/user-attachments/assets/766591a8-3b85-4e8a-9691-a92bf172f6bc" />
<img width="1234" alt="4ee38418842d3ad814bfa940d6f49fc" src="https://github.com/user-attachments/assets/ef601dda-7724-43aa-a938-08df6a28961f" />
<img width="1240" alt="c507ed58ef18a05f4deea917ea09c0e" src="https://github.com/user-attachments/assets/fe9d4675-454a-4672-aa86-43787668eb85" />
<img width="1267" alt="d9025b99df2a3a3c4838760dc64a445" src="https://github.com/user-attachments/assets/fb33656c-f567-48f4-9516-f21b2a248ff3" />
<img width="1280" alt="96d1323d17d87e0882210c8af47f543" src="https://github.com/user-attachments/assets/c9c65e2c-f338-4df0-87bd-4753ffc672ae" />


## 🛠 技术栈

- **前端**：Vue.js + Vuex  
- **后端**：Spring Boot + MyBatis + Shiro + Netty  
- **数据库**：MySQL  
- **文件存储**：MinIO（对象存储服务）

---

## 🌟 核心功能模块

### 4.1 用户管理模块

- 用户注册与登录  
- 个人信息管理  
- 个人资料完善（身材、肤色、风格偏好等）  
- 消息通知管理（系统通知、私信等）

### 4.2 服饰推荐与学习模块

#### 🧠 智能推荐

- 基于用户特征（身材、肤色）智能服饰推荐  
- 根据穿衣风格推荐（如日系、通勤、韩风、性感等）  
- 根据使用场合推荐（如约会、职场、校园、宴会等）

#### 🔍 搜索与筛选功能

- 关键词搜索  
- 按服装分类筛选（上装、下装、套装等）  
- 按服装材质筛选（棉、麻、丝、呢等）  
- 按应用场合筛选（休闲、聚会、婚礼等）

#### ✨ 搭配分享功能

- 文字描述搭配理念  
- 图片上传（支持单图、多图）  
- 短视频展示搭配效果  
- 关联服饰品牌或店铺链接（支持跳转）

### 4.3 妆容推荐与学习模块

#### 🧠 智能妆容推荐

- 基于用户肤色、五官特征进行智能妆容推荐  
- 按妆容类型推荐（淡妆、浓妆、职业妆、舞台妆等）

#### 🔍 搜索与筛选功能

- 支持关键词搜索妆容  
- 支持按妆容类型进行筛选

#### 💄 妆容分享功能

- 富文本描述化妆过程（含步骤说明、技巧分享）  
- 支持图片和视频上传  
- 可关联所使用的化妆品信息（品牌、系列、色号等）

### 4.4 化妆品与服饰分类管理模块

#### 👗 服饰分类管理

- 服装类型管理（上衣、裙子、裤子等）  
- 材质类型管理（棉、麻、丝等）  
- 应用场合管理（职场、运动、约会等）

#### 💋 化妆品分类管理

- 按用途分类管理（底妆、眼妆、唇妆等）  
- 品牌管理  
- 肤质适用性管理（干性、油性、敏感性等）

#### 🛒 商品交易功能

- 用户搭配作品支持挂载商品信息  
- 支持购买交易（跳转商城或内嵌支付）

### 4.5 留言及评论模块

- 支持点赞功能  
- 支持留言互动功能  
- 评论功能支持二级评论（回复他人）  
- 评论内容形式丰富：
  - 文字评论  
  - 表情评论  
  - 图片评论（单张/多张）

---

## 🚀 项目部署指南

### ✅ 环境要求

| 环境组件 | 版本要求 |
|----------|----------|
| JDK      | 11 及以上 |
| Node.js  | 16 及以上 |
| MySQL    | 8 及以上 |
| MinIO    | 任意稳定版本 |

---

### ▶ 后端启动步骤

```bash
# 1. 进入后端项目目录
cd backend

# 2. 使用 Maven 构建项目
mvn clean package

# 3. 启动 Spring Boot 应用
java -jar target/makeup-fashion.jar
```

---

### ▶ 前端启动步骤

```bash
# 1. 进入前端项目目录
cd frontend

# 2. 安装依赖
npm install

# 3. 启动前端项目
npm run serve
```

---

### ▶ MinIO 配置说明

```bash
# 启动 MinIO 示例命令
minio server /data --console-address ":9001"
```

- 控制台地址：[http://localhost:9001](http://localhost:9001)
- 后端配置 application.yml：

```yaml
minio:
  endpoint: http://localhost:9000
  accessKey: your-access-key
  secretKey: your-secret-key
  bucketName: beauty-fashion
```

---

## 📁 项目目录结构

```
makeup-fashion/
├── backend/        # 后端 Spring Boot 项目
│   ├── src/main/   # Java 源码
│   ├── resources/  # 配置文件
│   ├── pom.xml     # Maven 配置
├── frontend/       # 前端 Vue 项目
│   ├── src/        # 页面与组件
│   ├── public/     # 静态资源
│   ├── package.json# 前端依赖配置
├── docs/           # 项目文档
├── README.md       # 项目说明
```

---

## 🧠 项目亮点

- 👗 智能穿搭与妆容推荐，基于用户特征个性化定制
- 💬 搭配分享与妆容学习平台，图文视频全支持
- ☁ 文件存储使用 MinIO，轻量高效可扩展
- 🔐 多角色权限管理系统（用户、品牌商、管理员）
- 🧪 适合作为毕业设计、女性产品平台原型、时尚社区原型

---

## 📌 注意事项

- 推荐部署时使用 Docker 管理 MinIO、MySQL 等服务
- 前端推荐通过 Nginx 提供访问并启用 HTTPS
- 所有配置项如数据库、存储路径、秘钥请务必更改为私有环境值


## 📄 License

本项目采用 MIT 协议，详情请见 [LICENSE](./LICENSE) 文件。
