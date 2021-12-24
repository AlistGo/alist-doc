---
sidebar_position: 9
---

# 示例样式
### 透明美女背景阴影
<style>
.chakra-ui-light{
  background-image:url("https://ae02.alicdn.com/kf/H9a75a92bb5654e62aca36441238be9c0l.png");
}
.main-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
.chakra-ui-light .main-box {
  background-color: rgba(255,255,255,0.2) !important;
}
.chakra-ui-light .readme-box {
  background-color: rgba(255,255,255,0.2) !important;
}
.readme-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
</style>

### 无边框阴影
```css
.chakra-ui-light{
  background-color: #FAF5FF;
}
.main-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
.chakra-ui-light .main-box {
  background-color: rgba(255,255,255,0.9) !important;
}
.chakra-ui-light .readme-box {
  background-color: rgba(255,255,255,0.9) !important;
}
.readme-box {
  border-radius: 15px !important;
  box-shadow: unset !important;
}
```
### 仿大白样式
```css
.chakra-ui-light{
  background-image: linear-gradient(120deg,#e0c3fc 0%,#8ec5fc 100%) !important;
  background-attachment: fixed;
}
.main-box {
  border-radius: 15px !important;
}
.chakra-ui-light .main-box {
  background-color: white !important;
}
.chakra-ui-light .readme-box {
  background-color: white !important;
}
.readme-box {
  border-radius: 15px !important;
}
```
:::tip
如果你有好看的样式想要分享出来，可以点击下方的[Edit this page](https://github.com/Xhofe/alist-doc/edit/main/docs/style.md)发起pr将你的样式添加到本页面。
:::
