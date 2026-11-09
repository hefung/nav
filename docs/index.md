---
layout: home
hero:
  name: 技海拾珍
  text: 精选好工具
  tagline: 收集开发AI、办公、设计、图库站点。
  image:
    src: /logo.png
    alt: HeFung Logo
  actions:
    - theme: brand
      text: 开始浏览
      link: /ai/
    - theme: alt
      text: 打赏赞助
      link: https://hefung.github.io/sponsor.html
    - theme: alt
      text: GitHub
      link: https://github.com/hefung/nav
features:
  - icon: 📖
    title: 编程物语
    details: 整理前端常用知识网站，学习各种编程语言。
    link: /coding/common-framework/
    linkText: 前端网站
  - icon: 📘
    title: 常用AI
    details: 收集一些常用的AI工具，提高工作效率。
    link: /ai/
    linkText: AI网站
  - icon: 💡
    title: 辅助办公
    details: 收集一些常用的办公软件，提高工作效率。
    link: /office/
    linkText: 办公资源
  - icon: 🧰
    title: 设计灵感
    details: 收集一些常用的设计网站，提高设计水平。
    link: /design/
    linkText: 学习网站
  - icon: 🐞
    title: 科普娱乐
    details: 收集一些常用的科普娱乐网站，丰富业余生活。
    link: /popular-science/
    linkText: 科普网站
  - icon: 💯
    title: 吾志所向，一往无前。
    details: '<small class="bottom-small">一个小小的全栈开发</small>'
    link: https://github.com/hefung
---

<script setup>
import { FRIEND_DATA } from './home/friend-data'
</script>
<style src="./home/index.scss"></style>

<MNavLinks v-for="{title, items} in FRIEND_DATA" :title="title" :items="items"/>

<br />

::: tip
该导航由 [hefung](https://github.com/hefung/) 开发，如有引用、借鉴的请保留版权声明：<https://github.com/hefung/nav>
:::
