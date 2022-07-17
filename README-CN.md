# Hexon-plus

## 使用前提

首先，您需要 pnpm 的环境！如何安装 pnpm？输入安装 pnpm 的说明：

```
npm install pnpm -g
```


## 🎉 新名称

winwin-hexo-editor已更名为Hexon witch，意思是hexo在线。祝你喜欢它！

## ⭐️ 特征

-帖子和页面管理
-前置物模板
-~~在线图像管理~~使用[imageur](https://github.com/YuJianghao/imageur)

## 📘 指导

### 安装之前

确保您的```git```、```hexo```和```Node```、```js```的工作流程很好。```Hexon-plus```只为这些命令提供```GUI```，但**没有实现它们**。

### 安装

```bash
git clone https://github.com/gethexon/hexon
pnpm install
pnpm run setup
```

### 卸载

```bash
rm -rf hexon
# just remove the folder you just cloned
```

### 开始

```bash
pnpm start # 对于普通节点
pnpm prd # 对于pm2
```

### 更新

Hexon仍在开发中，因此只需从fresh重新安装即可避免错误。

## 💻 命令

- `pnpm run setup`: 安装和配置
- `pnpm start`: 使用节点启动hexon
- `pnpm prd`: 使用pm2启动hexon
- `pnpm resetpwd`: 重置密码
- `pnpm script`: 管理自定义脚本

## 🖥️ 发展

- 查看```开发```分支。
- 运行```pnpm dev init```安装依赖项并配置```hexon```。
- 运行```pnpm dev```，展示你的魔力！

## 💩 有麻烦吗？

- 阅读下面的常见问题。
- 尝试在[问题列表](https://github.com/gethexon/hexon/issues)中找到答案.
- 提出[问题](https://github.com/gethexon/hexon/issues/new).

**尽量不要通过QQ群提问。QQ群中的解决方案不会帮助他人.**

## ❓ 想知道更多吗？

开始[讨论](https://github.com/gethexon/hexon/discussions)或者通过QQ群59035610加入我们。

## 👌🏻 常见问题

### 404 Error

还原代理配置中可能存在错误（例如Nginx或Apache配置）。为了验证，在服务器上使用```curl```直接请求资产，而不使用任何还原代理。这应该是一个如下所示的命令：

```bash
curl http://localhost:5777/assets/HMonacoEditor.5101bbae.js
```

或hexon故障。提出一个问题。

## ⏱️ 寻找旧版本？

v0.6版本。x在[winwin hexo编辑器](https://github.com/YuJianghao/winwin-hexo-editor/)上仍然可用

## 版权

GPL-3.0 © winwin2011

具体使用可以查看[我的博客](https://tonywdy.github.io/)
# 不是作者的博客！
