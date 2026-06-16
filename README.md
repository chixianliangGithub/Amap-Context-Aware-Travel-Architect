# 🌍 Amap Context-Aware Travel Architect

> 基于 OpenSpec 规范与高德开放平台 API 的下一代「情境感知」智能差旅与自媒体文风转换引擎。

本项目严格按照 OpenSpec 2.1.0 契约驱动设计，将高德开放平台的路径规划、沿途搜索等核心能力封装为声明式接口，完美打通 OpenCode 智能体终端与各大 AI 编辑器生态。

## 🌟 核心卖点
- **100% 纯人类风（反 AI Slop）**：内置严格的文风过滤净化引擎，一键洗掉所有大模型塑料味，将高德 POI 物理轨迹秒变人间烟火气爆款微头条。
- **人情世故高级接待**：面向商务出行、领导接待，自动编排高德沿途高评分、带 VIP 休息室和独立泊车位的平整站点。
- **多依赖自驾护航**：针对长辈与两岁幼儿情绪极限，严格卡点 90 分钟疲劳期，自动过滤碎石、泥沙、高强度爬山等“推车火葬场”地形。

## 🔧 前置配置
本 SKILL 通过高德地图 Web 服务 API（HTTP 接口）获取数据，使用前需完成以下配置：
1. 访问 [高德开放平台](https://lbs.amap.com) 注册开发者账号。
2. 进入控制台 → 创建应用 → 选择「Web 服务」类型并获取 API Key。
3. 将 Key 配置到本地环境变量 `AMAP_API_KEY` 中即可。

## 📦 安装与使用教程
确保本地已安装运行标准 OpenSpec 规范的智能体终端（如 OpenCode），将本仓库克隆至你的本地全局技能目录：
```bash
cd ~/.config/opencode/skills/
git clone [https://github.com/chixianliangGithub/Amap-Context-Aware-Travel-Architect.git](https://github.com/chixianliangGithub/Amap-Context-Aware-Travel-Architect.git)
