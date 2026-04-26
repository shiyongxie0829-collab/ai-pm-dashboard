# AI产品经理学习Dashboard - 使用说明

## 📁 文件说明

你现在拥有3个版本的Dashboard:

### 1. **AI_PM_Learning_Dashboard.html**
- 原始无保护版本
- 包含所有学习资源和可点击链接
- 适合本地使用

### 2. **AI_PM_Dashboard_Public.html**
- 公开版本(与原始版本相同)
- 可直接分享或部署到网页
- 无密码保护

### 3. **AI_PM_Dashboard_Protected.html** 🔐
- 密码保护版本
- **密码**: `1_4m_7h3_0n3_4nd_0nly_r0s3`
- 包含登录界面和退出登录功能
- 适合公开部署但限制访问

---

## 🌐 部署到网页的方法

### 方法1: GitHub Pages (免费推荐)

1. 创建GitHub账号 (https://github.com)
2. 创建新repository,命名如 `ai-pm-dashboard`
3. 上传HTML文件:
   ```bash
   git init
   git add AI_PM_Dashboard_Protected.html
   git commit -m "Add AI PM Dashboard"
   git branch -M main
   git remote add origin https://github.com/你的用户名/ai-pm-dashboard.git
   git push -u origin main
   ```
4. 在Repository Settings → Pages → 选择main分支
5. 访问: `https://你的用户名.github.io/ai-pm-dashboard/AI_PM_Dashboard_Protected.html`

### 方法2: Netlify (超简单,免费)

1. 访问 https://www.netlify.com
2. 拖拽HTML文件到Netlify Drop
3. 立即获得网址,如: `https://random-name-12345.netlify.app`
4. 可自定义域名

### 方法3: Vercel (免费)

1. 访问 https://vercel.com
2. 导入GitHub repository 或直接上传文件
3. 自动部署,获得网址

### 方法4: Cloudflare Pages (免费)

1. 访问 https://pages.cloudflare.com
2. 连接GitHub或上传文件
3. 免费CDN加速

### 方法5: 简单HTTP服务器 (测试用)

如果只是想快速测试网页效果:

```bash
# Python 3
python -m http.server 8000

# 然后访问: http://localhost:8000/AI_PM_Dashboard_Protected.html
```

---

## 🔐 密码保护说明

### 当前密码
```
1_4m_7h3_0n3_4nd_0nly_r0s3
```

### 如何修改密码

在 `AI_PM_Dashboard_Protected.html` 中找到这一行(约第1058行):
```javascript
const correctPassword = "1_4m_7h3_0n3_4nd_0nly_r0s3";
```

修改为你想要的新密码即可。

### 安全提示

⚠️ **重要**: 这种密码保护是前端验证,密码存储在HTML源代码中。任何人查看页面源代码都能看到密码。

**如果需要真正安全的保护**,建议:
- 使用服务器端验证
- 或使用Cloudflare Access等服务
- 或部署到需要登录的平台(如Notion、Confluence)

对于学习资源dashboard,当前的前端密码保护已足够。

---

## 📊 Dashboard功能

### ✅ 已实现功能

1. **30天学习路径** - 4个阶段,每个任务可点击跳转
2. **40+ 学习资源链接** - 包括:
   - 免费课程 (Coursera, Google, Great Learning)
   - 付费认证 (Product School, Maven, IBM)
   - 官方文档 (Anthropic, Claude API)
   - 社区资源 (Reddit, Medium, GitHub)
3. **核心能力矩阵** - 6大技能分类
4. **方法论框架** - 8个核心框架
5. **30天行动计划** - Week-by-week任务清单
6. **精选资源卡片** - 一键跳转学习

### 🎨 交互功能

- 所有外部链接在新标签页打开
- 鼠标悬停高亮效果
- 密码登录/退出功能
- 响应式设计,支持移动端

---

## 🚀 快速开始

### 本地使用
1. 双击 `AI_PM_Dashboard_Protected.html`
2. 输入密码: `1_4m_7h3_0n3_4nd_0nly_r0s3`
3. 开始学习!

### 网页部署(推荐 Netlify)
1. 访问 https://app.netlify.com/drop
2. 拖拽 `AI_PM_Dashboard_Protected.html` 文件
3. 获得公开网址,如: `https://ai-pm-learning.netlify.app`
4. 分享给需要的人,告诉他们密码

---

## 💡 使用建议

1. **Week 1**: 每天花1-2小时学习基础课程
2. **Week 2-3**: 开始动手实践,构建AI原型
3. **Week 4**: 整合知识,准备面试或作品集
4. **持续**: 跟踪Anthropic研究论文,保持学习速度

### 学习优先级

**高优先级**:
- Anthropic面试题库 (必做)
- Prompt Engineering Guide (每天练习)
- Claude API文档 (动手实践)

**中优先级**:
- Product School认证课程
- AI PM Bootcamp ($2,300)
- IBM AI PM认证

**长期投资**:
- Reddit PM社区讨论
- Medium文章输出
- 个人Prompt Library构建

---

## 📞 支持

如需修改Dashboard或添加新功能,可以:
1. 直接编辑HTML文件
2. 使用Claude Code继续优化
3. Fork到GitHub并贡献改进

---

## 🎯 目标

30天后,你应该能够:
- ✅ 理解AI/ML核心概念
- ✅ 掌握主流AI PM方法论
- ✅ 构建3个AI产品原型
- ✅ 完成1个完整的AI产品PRD
- ✅ 准备好Anthropic PM面试

**Let's become an Anthropic-level AI PM! 🚀**

---

*Dashboard版本: 1.0*
*创建日期: 2026-04-27*
*密码: 1_4m_7h3_0n3_4nd_0nly_r0s3*
