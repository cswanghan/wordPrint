# 单词抄写PDF生成器 📝

一个功能强大的中英文单词描红练习册生成工具，帮助学习者通过手写练习提高英语单词记忆效果。

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/cswanghan/wordPrint)

## ✨ 主要特性

### 📚 智能字库管理
- **内置词库**：KET、TOEFL、GRE等分级词汇
- **自定义字库**：创建、编辑、删除个人词库
- **本地存储**：自动保存用户自定义内容
- **批量管理**：支持一键导入词汇列表

### 🎨 字体管理系统
- **实时预览**：所见即所得的字体效果
- **多种字体**：Helvetica、Courier、Times等标准字体
- **样式控制**：字体粗细、斜体等样式设置
- **自定义预览**：输入任意文本进行字体测试

### 🖨️ 专业打印设置
- **页面配置**：A4/Letter/Legal多种纸张规格
- **方向选择**：纵向/横向页面布局
- **边距控制**：精确的页边距自定义
- **页眉页码**：可选的页眉内容和页码显示

### 👁️ PDF预览功能
- **生成预览**：下载前查看文档信息
- **详细统计**：页数、单词数、字体等信息展示
- **质量保证**：确保输出符合预期

## 🚀 在线使用

### 方法一：GitHub Pages
访问：`https://cswanghan.github.io/wordPrint/demo.html`

### 方法二：Vercel部署
1. 点击上方 "Deploy with Vercel" 按钮
2. 连接GitHub账户并导入项目
3. 自动部署完成，获得专属域名

### 方法三：本地运行
```bash
# 克隆项目
git clone https://github.com/cswanghan/wordPrint.git
cd wordPrint

# 启动本地服务器
python3 -m http.server 8000
# 或使用Node.js
npx serve .

# 浏览器访问
open http://localhost:8000/demo.html
```

## 📖 使用指南

### 基础使用
1. **选择词库**：从下拉菜单选择预设词库或手动输入
2. **调整格式**：设置描红遍数、行间距、字体大小等
3. **生成PDF**：点击生成按钮下载练习册

### 高级功能
1. **字库管理**：点击"📚 字库管理"创建个人词库
2. **字体设置**：点击"🔤 字体管理"预览和设置字体
3. **打印优化**：点击"🖨️ 打印设置"配置页面布局
4. **预览检查**：使用"👁️ 预览PDF"确认效果

## 🛠️ 技术栈

- **前端框架**：纯JavaScript ES6+
- **UI框架**：Tailwind CSS
- **PDF生成**：jsPDF库
- **数据存储**：localStorage
- **部署平台**：Vercel/GitHub Pages

## 📁 项目结构

```
wordPrint/
├── demo.html          # 主应用文件
├── README.md          # 项目说明
├── CLAUDE.md          # 开发指南
├── package.json       # 项目配置
├── vercel.json        # 部署配置
└── .git/              # Git版本控制
```

## 🎯 应用场景

### 教育机构
- **语言学校**：制作标准化练习册
- **培训机构**：个性化学习材料
- **国际学校**：分级词汇练习

### 个人学习
- **考试备考**：TOEFL、GRE、雅思词汇练习
- **日常学习**：自定义单词本练习
- **儿童教育**：基础词汇描红练习

### 家庭教育
- **家长辅导**：制作个性化练习册
- **在家学习**：随时生成练习材料
- **进度跟踪**：分阶段词汇练习

## 🌟 功能特色

### 教育专业性
- **描红设计**：标准四线格练习格式
- **视觉引导**：清晰的字母基线系统
- **重复练习**：可调节的描红遍数
- **进阶学习**：从描红到独立书写

### 用户体验
- **响应式设计**：支持桌面和移动设备
- **直观操作**：简单易用的用户界面
- **即时反馈**：实时预览和设置更新
- **数据持久**：自动保存用户偏好

### 技术优势
- **无服务器**：纯前端应用，快速加载
- **离线支持**：下载后可离线使用
- **跨平台**：支持所有现代浏览器
- **开源免费**：MIT许可证，自由使用

## 🤝 贡献指南

欢迎提交Issue和Pull Request！

### 开发环境
```bash
# 克隆项目
git clone https://github.com/cswanghan/wordPrint.git
cd wordPrint

# 启动开发服务器
npm run dev
```

### 提交规范
- `feat: 新功能`
- `fix: 修复bug`
- `docs: 文档更新`
- `style: 样式调整`

## 📄 许可证

本项目基于 [MIT License](LICENSE) 开源。

## 🙏 致谢

- **jsPDF**: PDF生成核心库
- **Tailwind CSS**: 现代化CSS框架
- **Claude Code**: AI辅助开发工具

---

**⭐ 如果这个项目对您有帮助，请给个Star支持！**

[![GitHub stars](https://img.shields.io/github/stars/cswanghan/wordPrint?style=social)](https://github.com/cswanghan/wordPrint/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/cswanghan/wordPrint?style=social)](https://github.com/cswanghan/wordPrint/network/members)
[![GitHub issues](https://img.shields.io/github/issues/cswanghan/wordPrint)](https://github.com/cswanghan/wordPrint/issues)

**💬 交流反馈**：有问题或建议请提交Issue，我们会及时回复！