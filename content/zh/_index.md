# 创建标准的 Docsy 主题首页
cat > content/zh/_index.md << 'EOF'
---
title: "MacCMS Rust 文档"
menu:
  main:
    weight: 1
---

+++
# 首页内容配置
+++

{{< blocks/cover title="MacCMS Rust 文档" image_anchor="top" height="full" color="primary" >}}
<div class="mx-auto">
	<a class="btn btn-lg btn-primary mr-3 mb-4" href="/blog/">
		查看博客 <i class="fas fa-arrow-alt-circle-right ml-2"></i>
	</a>
	<a class="btn btn-lg btn-secondary mr-3 mb-4" href="/docs/">
		学习文档 <i class="fas fa-book ml-2"></i>
	</a>
	<p class="lead mt-5">基于 Hugo 和 Docsy 构建的现代化技术文档平台</p>
</div>
{{< /blocks/cover >}}
EOF
