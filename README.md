# AI图片工具箱

免费的在线AI图片处理工具，提供图片反推提示词和提示词生成图片功能。

## 功能特点

- **图片反推提示词**：上传图片，AI分析生成Midjourney/SD风格提示词
- **提示词生图**：输入描述文字，DALL-E/其他AI模型生成图片
- **多API支持**：支持OpenAI、硅基流动、火山引擎等多种AI服务

## 在线使用

访问: https://你的域名.com

## 部署到GitHub Pages

1. 创建新仓库：`pannuo/ai-image-tools`
2. 上传所有文件
3. Settings → Pages → Source: Deploy from a branch → main
4. 添加CNAME文件（填入你的域名）

## 域名配置（Namecheap）

在Namecheap的DNS设置中添加：

| 类型 | 主机名 | 值 |
|------|--------|-----|
| CNAME | www | pannuo.github.io |
| CNAME | @ | pannuo.github.io |

等待5-30分钟生效。

## 技术栈

- 纯HTML/CSS/JavaScript（无框架依赖）
- 支持多种AI API服务商
