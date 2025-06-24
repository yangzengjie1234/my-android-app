# 填空题练习 Android 应用

一个基于Kivy框架开发的Android填空题练习应用，支持多种练习模式和云端构建。

## 功能特点

### 📱 移动端优化
- 触摸友好的用户界面
- 适配Android手机屏幕
- 流畅的操作体验

### 🎯 练习模式
- **顺序练习**：按题目顺序依次练习
- **随机练习**：随机打乱题目顺序
- **错题练习**：专门练习答错的题目
- **收藏练习**：练习收藏的重点题目
- **学习模式**：不计时不统计，可查看答案

### 📊 智能统计
- 实时显示答题进度
- 统计正确率和用时
- 自动保存练习记录
- 错题自动收集

### 📁 文件支持
- 支持 `.txt` 格式题目文件
- 简单的题目格式：题目 + 答案
- 示例文件已包含

## 🚀 快速开始

### 📚 选择适合您的指南

- **🔰 完全新手**：[新手快速上手.md](新手快速上手.md) - 5分钟学会制作Android应用
- **📖 详细教程**：[详细操作指南.md](详细操作指南.md) - 手把手分步指导
- **🔧 技术文档**：[云端构建指南.md](云端构建指南.md) - 深入技术细节

### 🎯 一键开始

**最简单的方法**：
```bash
# 运行快速开始脚本
python quick_start.py
```

这个脚本会自动：
- ✅ 检查Python环境
- ✅ 安装必要依赖
- ✅ 启动应用测试
- ✅ 显示构建指导

### 📱 制作Android应用

#### 🌐 云端构建（推荐 - 零配置）

1. **创建GitHub仓库**并上传代码
2. **等待自动构建**（15-30分钟）
3. **下载APK文件**安装到手机

详细步骤请查看：[新手快速上手.md](新手快速上手.md)

#### 💻 本地构建（需要Linux环境）

```bash
# 安装buildozer
pip install buildozer

# 构建APK
buildozer android debug
```

**注意**：Windows不支持本地构建，请使用云端构建。

## 题目格式

创建 `.txt` 文件，格式如下：

```
题目标题

1. 这是第一道______题目。
答案：填空

2. Python是一种______编程语言。
答案：解释型

3. Android应用的安装包格式是______。
答案：APK
```

## 项目结构

```
├── main.py                    # 应用入口
├── android_app.py             # Kivy应用主程序
├── buildozer.spec             # Android构建配置
├── sample.txt                 # 示例题目文件
├── .github/workflows/         # GitHub Actions配置
│   └── build-android.yml
├── 云端构建指南.md             # 详细构建指南
└── README.md                  # 项目说明
```

## 云端构建服务

本项目支持多种云端构建服务：

- ✅ **GitHub Actions**（推荐）- 免费、简单、可靠
- ✅ **GitLab CI/CD** - 企业级CI/CD
- ✅ **Travis CI** - 经典CI服务
- ✅ **CircleCI** - 现代CI平台

详细配置请参考 [云端构建指南.md](./云端构建指南.md)

## 构建状态

[![Build Android APK](https://github.com/你的用户名/填空题练习/actions/workflows/build-android.yml/badge.svg)](https://github.com/你的用户名/填空题练习/actions/workflows/build-android.yml)

## 版本历史

- **v1.0** - 基础功能实现
  - 多种练习模式
  - 学习模式支持
  - 错题和收藏管理
  - Android适配

## 技术栈

- **Python 3.9+** - 主要编程语言
- **Kivy 2.3+** - 跨平台UI框架
- **Buildozer** - Android打包工具
- **GitHub Actions** - 自动化构建

## 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 联系方式

如有问题或建议，请：
- 提交 [Issue](https://github.com/你的用户名/填空题练习/issues)
- 发起 [Discussion](https://github.com/你的用户名/填空题练习/discussions)

---

⭐ 如果这个项目对你有帮助，请给个Star支持一下！
