## 前言
- 这是一份对于Android知识体系，根据知识图谱的方式来进行组织的在线查找库。同时作为自身学习过程及知识体系搭建的过程记录。
- 知识体系部分主要涵盖计算机基础，Java，Android，Kotlin，Flutter等内容
- 实践部分则集合了一些用于练手实践的demo项目，以及一些涵盖其他行业技术的创意项目
- 软技能的部分会收集一些产品、管理相关内容的读后感或者是思考分享

-------------
# 000 计算机基础
## 010 计算机组成原理
### 011 计算机组成结构
### 012 数制和编码
### 013 处理器系统
### 014 存储系统
### 015 I/O系统

## 020 计算机网络
### 021 计算机网络基础
### 022 底层网络协议
- TCP/IP
- UDP
### 023 应用层网络协议
- DNS
- HTTP
- HTTPS
- MQTT
### 024 网络技术
- CDN
- Nginx代理服务

### 025 网络调试工具
- 网络调试命令
- postman
- https抓包
  
## 030 操作系统
### 031 操作系统基础
### 032 操作系统启动过程
### 033 进程管理
### 034 内存管理
### 035 文件管理
### 036 I/O管理
### 037 IPC进程间通信

## 040 数据结构与算法
### 041 基础数据结构
- 线性表
- [散列表](https://github.com/PractiseForTwoAndHalfYear/AndroidKnowMap.github.io/blob/main/notes/%23000计算机基础/散列表.md)
- 队列
- 栈
- 二叉树
- 其他数据结构
### 042 高级数据结构
- 前缀和，数组
- 差分数组
- 单调队列
- 单调栈
- 并查集
- 二叉堆
- 图
- 布隆过滤器
### 043 算法设计基础
- 复杂度分析
- 递归
- 分治算法
- DFS、BFS
- 回溯算法
- 贪心算法
- 动态规划
### 044 经典算法题
- 二分查找
- 排序算法
## 050 数据库

## 060 设计模式
### 061 创建型
### 062 结构型
### 063 行为型

-------------

# 100 Java
## 110 Java编程
### 111 Java String
### 112 Java 集合
- ArrayList
- CopyOnWriteArrayList
- LinkedList
- HashMap
- LinkedHashMap实现LRU
- WeakHashMap和HashMap的区别

## 120 JVM
### 121 JVM内存管理
#### 121.1 内存分布模型
#### 121.2 垃圾回收机制
#### 121.3 对象创建过程
#### 121.4 对象的内存组成
#### 121.5 java的四种引用类型

### 122 Java编译过程
#### 122.1 Class文件结构
#### 122.2 编译过程
#### 122.3 类加载机制
#### 122.4 泛型
#### 122.5 注解
#### 122.6 平台无关性

### 123 JVM执行系统
#### 123.1 方法调用及返回
#### 123.2 重载和重写
#### 123.3 反射机制
#### 123.4 异常机制

## 130 并发编程
- ThreadLocal

## 140 Kotlin编程
### 141 协程
### 142 拓展函数(with, let)
### 143 by委托机制
-------------

# 200 Android
## 210 Android四大组件
## 220 Android核心原理
### 221 Android IPC通信
[安卓常见通信机制](https://blog.51cto.com/u_16213711/7235486)
- Content Provider
- Broadcast
- AIDL
### 222 Android虚拟机
### 223 Android系统层服务
### 224 Android应用层机制
#### 224.1 Handler机制
#### 224.2 事件分发机制
#### 224.3 Window机制
#### 224.4 视图框架
#### 224.5 布局解析
#### 224.6 绘制机制
#### 224.7 ANR机制
#### 224.8 LayoutInflater

### 225 Android编译过程
### 226 Android资源管理机制

## 230 Android核心特性
### 231 Android版本适配
### 232 权限机制
### 233 系统通知
### 234 持久化存储
### 235 网络请求
### 236 桌面微件Widget

## 240 Android组件原理
### 241 Jetpack组件
#### 241.1 LiveData
[LiveData]()
### 242 网络组件
### 243 序列化组件
### 244 持久化组件
### 245 调优组件
### 246 其他

## 250 Android UI开发
### 251 Android UI基础
### 252 文本
### 253 图片
### 254 动画
### 255 交互
### 256 高级组件
- 256.1 SurfaceView
- 256.2 NestedScrollView
- 256.3 RecyclerView

## 260 Android 性能优化

## 270 Android 工程化
### 271 Gradle构建工具
### 272 AGP插件
### 273 组件化开发
### 274 AOP面向切面
### 275 应用测试
### 276 动态化
### 277 安全与逆向

## 280 Compose
-------------

# 300 NDK开发
## 310 C/C++基础
### 311 C基础
### 312 C++基础

## 320 JNI基础

## 330 NDK基础
### 331 NDK编译基础：ndk-build & CMake
### 332 so文件格式
### 333 一键检索未适配64位架构的so文件
### 334 so文件动态化
### 335 so文件精简
### 336 Native内存泄漏监控

## 340 音视频
### 341 H.264视频压缩编码
### 342 音频压缩编码
### 343 FFMPEG
-------------

# 400 DevOps
## 410 Git 版本控制
## 420 CI/CD 持续集成
### 421 jenkins

## 430 开源
### 开源组件到MavenCentral仓库
-------------

# 500 前端
## 510 Flutter
## 520 Unity 
-------------

# 600 后端
-------------

# 700 项目实践
## 710 机制demo
### 711 日夜切换
### 712 埋点
### 713 可见即可说

## 720 实际应用
### 721 地图
### 722 语音
### 723 launcher

## 730 创意应用
### 731 3D相机、相册
-------------

# 800 PM & UI/UE/UX & Marketing & Operation
互联网行业常见的职位及其缩写如下：
1. **CTO（技术总监）**：负责技术研发和团队管理，确保技术方案的实施和系统的稳定运行。
2. **CFO（首席财务官）**：负责公司的财务管理和投资决策。
3. **CEO（首席执行官）**：负责公司的整体运营和管理，制定公司战略和业务发展计划。
4. **COO（运营团队负责人）**：负责公司的日常运营和管理，包括人力资源、行政、市场等部门。
5. **PM（产品经理）**：负责产品的规划、设计和管理，包括需求调研、产品设计、项目管理等。
6. **RD（研发）**：负责软件或硬件的开发和实现，包括前端开发、后端开发、移动端开发等。
7. **FE（前端开发）**：负责Web或移动应用的前端开发和用户体验优化。
8. **QA（测试）**：负责产品的测试和质量保证，确保产品的稳定性和性能。
9. **UE/UX（用户体验设计师）**：负责产品的用户体验设计，包括用户调研、原型设计、界面优化等。
10. **UI（用户界面设计师）**：负责产品的用户界面设计，包括图标、按钮、布局等。
11. **DBA（数据库管理员）**：负责数据库的管理和维护，确保数据库的安全、稳定和高效运行。
12. **OP（运维）**：负责产品的部署、维护和监控，确保产品的持续稳定运行。

# 900 软技能 
## 910 架构类
## 920 管理类
## 930 游戏类