好消息！现在提供 Smart HOJ Vue。

[在线 Demo](https://oj.lsnas.xyz/)

## 介绍

Smart HOJ Vue 部署在 Github Pages 上，可以提供更好的前端体验，基于 HOJ 的自定义美化脚本 Smart HOJ 和 hoj-vue 实现。

Smart HOJ Vue 连接到 [Deeplearning](https://deeplearning.org.cn)。

> 为什么不连接到 SSFOJ?
> 
> SSFOJ 是一个不错的选择，测试时一切正常，直到部署时……

<li>Github Pages 强制采用 https 协议，导致往 <code>http://ssf.hdoi.cn</code> 发送的请求全部变成 https，所以不可行。</li>
<li>你可以尝试访问 <code>https://ssf.hdoi.cn</code>，然后你就会明白了。</li>

加载时间可能很长，似乎会加载很多不存在的的 CSS 和 JS 然后 503。

## 伟大的计划

- 20250818 初步完成
- 20250819 部署
- 20250820 完善管理员后台，修复图像问题。

目前 CF JSESSION 更新还需要前往原网站，部分细节尚未实现。

我们会尝试让这个前端具备更多功能，并持续维护，保证不出现 Bug。

## 鸣谢
@张书瑞：Smart HOJ 作者。

@罗及恩：技术支持

@白熔鑫：Better HOJ 计划提出者
