# GitHub 从零配置 · 练习仓库

这是跟随「Git GitHub 国内上手指南」创建的第一个仓库，用来练习提交与推送。

## 本次配置记录

- Git 版本：2.55.0
- 分支：main
- 提交身份：占位值（Your Name / you@example.com），后续需改成真实信息
- 认证方式：HTTPS + PAT（个人访问令牌）
- 国内网络：GitHub 直连时通时断，已记录可用镜像 `https://gh-proxy.org`

## 待完成

1. 注册 GitHub 账号
2. 生成 Personal Access Token（勾选 repo 权限）
3. 用 `gh auth login --with-token` 完成认证
4. 创建远程仓库并推送

## 如何修改提交身份

```bash
git config --global user.name "你的姓名"
git config --global user.email "你的邮箱"
```

## 第一次练习提交

这是第 1 课「提交与推送」加上去的一行。
