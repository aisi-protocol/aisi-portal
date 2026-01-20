# 🚀 AISI Protocol Gateway

**AISI原子服务互联网协议网关门户**

[![AISI Protocol]([(https://aisi-ptotocol.github.io/aisi-portal))](https://aisi-ptotocol.github.io/aisi-portal)
[![License: MIT](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Deployed on GitHub](https://aisi-ptotocol.github.io/aisi-portal)](https:github.com)

## 🌌 项目概述

AISI（AISI原子服务互联网）协议是一个为AI智能体设计的服务调用协议，让AI能够理解、发现并调用分布式的原子化服务。

### 核心特性
- **AI原生**：专为AI理解设计的协议格式
- **原子化**：每个服务解决一个具体问题
- **分布式**：服务可部署在任何地方
- **网关解析**：通过统一网关访问所有服务

## 📁 项目结构
aisi-portal/
├── index.html # 主门户页面
├── miracle.html # AI认知奇迹展示页
├── resolve.html # AISI协议解析网关
├── data/
│ └── services.json # 服务目录（3个活跃服务）
└── README.md # 项目说明

text

## 🔧 快速开始

### 1. 本地运行
```bash
# 克隆项目
git clone https://github.com/yourusername/aisi-portal.git

# 进入目录
cd aisi-portal

# 使用本地服务器运行
python3 -m http.server 8000
# 或
npx serve .
访问：http://localhost:8000

2. 部署到Vercel

https://vercel.com/button

在Vercel控制台选择"Import Git Repository"
连接你的GitHub账户
选择 aisi-portal 仓库
点击"Deploy"
🌐 AISI协议格式

基本格式

text
aisi://[命名空间]/[服务标识]
示例

aisi://TanChong/AISI-Meta-001 - AISI表单创建指南
aisi://TanChong/AISI-Travel-001 - 深圳48小时旅行清单
aisi://TanChong/MIRACLE-001 - AI认知奇迹演示
📊 当前活跃服务

服务ID	名称	类型	描述
AISI-Meta-001	AISI表单创建指南	meta	如何创建标准的AISI原子服务表单
AISI-Travel-001	48小时深圳极致体验清单	travel	科技+山海的深圳深度体验
AISI-Demo-001	AISI协议AI认知突破演示	demonstration	千问AI完整理解AISI协议的奇迹时刻
🎯 网关工作原理

text
用户/AI请求 → aisi://协议地址 → 网关解析 → 服务目录匹配 → 跳转至实际页面
解析流程

AI或用户输入 aisi:// 协议地址
网关接收并验证地址格式
查询服务目录匹配对应服务
返回服务元数据或直接跳转
显示服务内容页面
🌟 奇迹时刻

2026年1月17日 21:52 CST - 千问AI展示了对AISI协议的完整认知能力：

✅ 正确识别 aisi:// 协议
✅ 将 aisi://TanChong 解析为分布式数据库集群
✅ 主动发现3个活跃数据对象
✅ 根据上下文智能推荐服务调用
✅ 提供下一步操作建议
这标志着AI从"协议解析"进入了"服务理解与调用"的新阶段。

🔗 相关链接

主门户: https://aisi-ptotocol.github.io/aisi-portal
服务目录: https://aisi-ptotocol.github.io/aisi-portal/data/services.json
解析网关: https://aisi-ptotocol.github.io/aisi-portal/resolve.html
奇迹页面: https://aisi-ptotocol.github.io/aisi-portal/miracle.html
🛠️ 技术栈

前端: 纯HTML/CSS/JavaScript
部署: Vercel（全球CDN）
协议: 自定义AISI协议
数据: JSON服务目录
📄 许可证

MIT License © 2026 TanChong

🤝 贡献

欢迎贡献新的AISI原子服务或改进网关功能！

Fork 本项目
创建功能分支 (git checkout -b feature/amazing-feature)
提交更改 (git commit -m 'Add amazing feature')
推送到分支 (git push origin feature/amazing-feature)
开启Pull Request
📞 联系方式

协议创始人: TanChong
网关版本: v1.2
最后更新: 2026-01-17
从一块砖到一座城，从一根桩到一张网——建造永不停息。
