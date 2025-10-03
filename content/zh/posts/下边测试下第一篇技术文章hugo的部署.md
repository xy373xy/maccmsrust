---
title: 下边测试下第一篇技术文章hugo的部署
date: 2025-10-03T03:18:53.804Z
description: 下边测试下第一篇技术文章hugo的部署
categories: 技术教程
tags:
  - hugo
  - 技术
draft: false
---
# 创建简单的测试文章
hugo new zh/posts/test-article.md

# 编辑内容
cat > content/zh/posts/test-article.md << 'EOF'
---
title: "测试文章"
date: 2024-01-15T10:00:00+08:00
draft: false
categories: ["技术教程"]
tags: ["test"]
slug: "test-article"
---

这是测试文章内容。
EOF

# 提交并推送
git add .
git commit -m "添加测试文章"
git push origin main