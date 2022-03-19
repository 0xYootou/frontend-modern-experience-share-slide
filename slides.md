---
theme: unicorn
background: https://source.unsplash.com/collection/94734566/1920x1080
highlighter: shiki
lineNumbers: true
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Web 体验技术发展前沿
fonts:
  local: "LXGWWenKai-Regular"
---

<style>

*{
  text-shadow: 1px 1px 0px #ddd;font-family: "LXGWWenKai-Bold" !important;
}
h1,h2,h3,h4,h5 {
  
  text-shadow:none;

}
</style>

# Web 体验技术发展前沿

本文内容具有一定局限性，不代表社区真实现状，仅做参考！

今天的分享有两个目的

- 大家可以作为团队技术方向选题的参考
- 可以分享给公司的产品设计老板等促进产品共创 <div>在线地址：<a href="https://frontshare.vercel.app">frontshare.vercel.app</a></div>

<div class="pt-12">
  <div>
     小芋头君 
  </div>
  <div>@yootou.com </div>
  <div>@yootou.eth @hacksdao.eth</div>
  
</div>

<div class="abs-br m-6 flex gap-2">
  <!-- <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button> -->
  <a href="https://github.com/yu-tou" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>
<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# 本文主要内容

- 实时体验（Realtime experience，偏产品）
- 在线协作（Online collaboration，偏产品）
- 快速建站（Jamstack）
- 浏览器计算能力
- 浏览器系统能力
- 移动端
- 区块链

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 核心感受

- 纯粹，简单/易用/单一功能做到最优/逻辑简单清晰
- 开放，保持开放/使用开放的技术/为开放的生态贡献力量
- 集成，提供插件能力/集成至其他产品/同时让其他产品集成进来
- 生态，合作打造生态理念/共同推进/互相成就

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;
  background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 为什么是 Web

## 什么是 Web？

互联网和万维网（WorldWideWeb）这两个名词经常被混用。然而，这两个名词的意思并不相同。互联网是一个全球互相连接的电脑网络系统。相较之下，万维网是由超链接和统一资源标志符连接的文件和其他资源的全球集合。万维网资源通常使用 HTTP 或 HTTPS 访问，是互联网通信协议的其中之一[20

可以把 Web 简单理解成由 W3C 主导指定标准，各浏览器厂商推动发展的基于 HTML/CSS/JAVASCRIPT 等一系列标准语言实现的互利网信息交换模式。

## 为什么是 Web？

- 全球化组织经过严格的流程慎重决定的标准
- 被全世界的浏览器广泛按照标准支持
- 有完善的安全保障设计
- 基于网络的实时交换和缓存策略设计
- 越来越贴近操作系统的能力，可以在安全、快捷的前提下更深度使用系统硬件软件能力

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 一 实时体验

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;
  background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 实时体验

<br/>

[https://vercel.com](https://vercel.com)

<br/>

在 2021 年 6 月，Next.js 框架背后的开发商 Vercel 在 C 轮融资中筹集了 1.02 亿美金，使其估值达到 11 亿美元，正式成为了一家独角兽企业。11 月份，Vercel 再次宣布获得新的融资，其在 D 轮融资中筹集了 1.5 亿美元，使其估值相比之前翻了一番，达到 25 亿美元。

- 70 CITIES
- 24B+ REQUESTS PER WEEK
- 10PB DATA SERVED
- 99.99% GUARANTEED UPTIME

<br/>

部署前端应用的云服务，也支持简单的服务端、存储等。

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# <svg role="img" aria-label="Vercel Inc." height="40" viewBox="0 0 283 64" fill="var(--geist-foreground)"><path d="M37 0l37 64H0L37 0zM159.6 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7h28.3c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM267.3 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7H267c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM219.3 28.3l6.8-3.9c-3.2-5-8.9-7.8-15.8-7.8-10.9 0-18.5 7.2-18.5 17.5s7.6 17.5 18.5 17.5c6.9 0 12.6-2.8 15.8-7.8l-6.8-3.9c-1.8 3-5 4.7-9 4.7-6.3 0-10.5-4.2-10.5-10.5s4.2-10.5 10.5-10.5c3.9 0 7.2 1.7 9 4.7zM282.3 5.6h-8v45h8v-45zM128.5 5.6h-9.2L101.7 36 84.1 5.6h-9.3L101.7 52l26.8-46.4zM185.1 25.8c.9 0 1.8.1 2.7.3v-8.5c-6.8.2-13.2 4-13.2 8.7v-8.7h-8v33h8V36.3c0-6.2 4.3-10.5 10.5-10.5z"></path></svg>

<br/>

## 核心特色

<br/>

- 产品定位和产品功能极简，官方定义：Develop. Preview. Ship.
- 部署过程极简，连接 Github 账号、导入 Github 项目、Deploy、Preview，最小步骤完成。
- 在 vercel 里部署应用的各种过程都不需要刷新页面，所有状态都会 <span style="color:#ff0000;">自动推进</span> 和 <span style="color:#ff0000;">实时生效</span>，触发往往只需一个点击

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# <svg role="img" aria-label="Vercel Inc." height="40" viewBox="0 0 283 64" fill="var(--geist-foreground)"><path d="M37 0l37 64H0L37 0zM159.6 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7h28.3c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM267.3 34c0-10.3-7.6-17.5-18.5-17.5s-18.5 7.2-18.5 17.5c0 10.1 8.2 17.5 19.5 17.5 6.2 0 11.8-2.3 15.4-6.5l-6.8-3.9c-2.1 2.1-5.2 3.4-8.6 3.4-5 0-9.3-2.7-10.8-6.8l-.3-.7H267c.2-1 .3-2 .3-3zm-28.7-3l.2-.6c1.3-4.3 5.1-6.9 9.9-6.9 4.9 0 8.6 2.6 9.9 6.9l.2.6h-20.2zM219.3 28.3l6.8-3.9c-3.2-5-8.9-7.8-15.8-7.8-10.9 0-18.5 7.2-18.5 17.5s7.6 17.5 18.5 17.5c6.9 0 12.6-2.8 15.8-7.8l-6.8-3.9c-1.8 3-5 4.7-9 4.7-6.3 0-10.5-4.2-10.5-10.5s4.2-10.5 10.5-10.5c3.9 0 7.2 1.7 9 4.7zM282.3 5.6h-8v45h8v-45zM128.5 5.6h-9.2L101.7 36 84.1 5.6h-9.3L101.7 52l26.8-46.4zM185.1 25.8c.9 0 1.8.1 2.7.3v-8.5c-6.8.2-13.2 4-13.2 8.7v-8.7h-8v33h8V36.3c0-6.2 4.3-10.5 10.5-10.5z"></path></svg>

<br/>

 <video src="/1.mp4" controls style="height:70%;border-radius:5px;" autoplay />

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 背后技术

<br/>

## Next.js

- The React Framework for Production
- hybrid static & server rendering, TypeScript support, smart bundling, route pre-fetching, and more

## SWR

![](/swr.vercel.app_zh-CN.png)

## Hyper

- https://hyper.is/
- a beautiful and extensible experience for command-line interface

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 二 在线协作

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

## 1. figma cursor chat

<br/>

<img src="/3.gif" style="height:60%">

<br/>

[https://github.com/yomorun/react-cursor-chat](https://github.com/yomorun/react-cursor-chat)

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

## 2. figma comments

<br/>

<img src="/4.gif" style="height:60%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

## 3. figma voice

<br/>

<img src="/5.png" style="width:60%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

## 3. figma voice

<br/>

<img src="/5.png" style="width:60%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

## 4. FigJam

<br/>

<img src="/6.png" style="height:60%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

## 5. Miro

<br/>

cursor chat & live chat & video chat & screen share & comments & collaborative editing

<video src="/7.mp4" controls style="height:70%;border-radius:5px;" autoplay />

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

## 5. 插件化

<br/>

<img src="/200.png"   style="height:70%;border-radius:5px;"  />

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# Figma

### 2021 年 6 月融资 2 亿美金，市值 100 亿美金

<br/>

# Miro

### 2022 年 1 月融资 4 亿美金，市值 175 亿美金

<br/>

有意思的是这些专业工具的一大核心初始卖点就是协同。

只是随着疫情格局变化，这种协同一直在被强化、扩展、创新（cursor chat）。

除了核心功能的协同，这些工具反向把 chat、meet、voice 搬到了工具内。

这么大的市值中，在线办公、在线会议的价值占比不会低，而不是单纯的设计工具或者白板工具。

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

## 6. Next.js live (vercel)

<br/>

https://vercel.com/live

Join/Draw/Chat/Code，这里不难理解为什么 vercel 要做 Next.js live，借鉴的是以上几个工具的颠覆思路

<img src="/8.png" style="width:58%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 技术框架

<img src="/9.png" style="width:50px;display:block; ">

<br/>

https://replicache.dev/

Replicache makes it easy to add realtime collaboration, lag-free UI, and offline support to web apps.

<img src="/10.png" style="width:50%">

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 三 快速建站

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# Jamstack

[https://jamstack.wtf/](https://jamstack.wtf/)

### DEFINITION

"JAM" stood for JavaScript / API / Markup。

可以认为 Jamstack 是一组开发网站的最佳实践，包括目标定义、最佳实践、工作流、实用工具等。一些云产品或者框架，遵循类似的理念实现。

### MEANING

Decoupled 前后端解耦 / Static-first 静态内容优先 / Progressively enhanced 渐进增强

### BEST PRACTICES

CDN 网络分发 / 原子化部署 / 缓存自动失效 / 版本管理 / 自动化构建

### WORKFLOW

Develop / Version Control / Automated build( assets. pre render. deploy.) / Update CDN.

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# DEVELOPMENT

### The Fullstack React Framework

- 基本、纯粹、场景无关的底层框架。
- Next.js。可能是使用最广泛的 Fullstack 框架，主要是其 SSR&SSG 能力，0 配置，及 Vercel 的无缝官方支持。
- Remix.js。知名团队最新出品的框架，主要是更强的前后端代码融合能力（同一个组件文件中），更好的加载体验（组件级别的 SSG）。

### Web Application Framework

- 通常是一系列基础工具的整合，例如 GraphQL、Prisma 等，将数据定义和服务开发等部分 less 掉。
- Redwood.js。an opinionated, full-stack, serverless-ready web application framework。
- Blitz.js。a batteries-included framework that features a "Zero-API" data layer abstraction that eliminates the need for REST/GraphQL

### Static Site Generators

- 主要用来建站、博客的一些工具框架，例如管理文章、主题、构建等，通常用来写博客、写文档等。
- Gatsby / Hugo / Jekyll / VuePress / Docsify / GitBook 等

### Site Builders

- 低代码搭建工具，如 Stackbit / Builder.io / CloudCannon

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# DYNAMIC PARTS

### 函数服务

- AWS lambda functions / Netlify Functions / Vercel Functions

### 数据管理

- Prisma / AirTable / Fauna / Hasura / MongoDB Atlas / AWS DynamoDB

### 表单工具

- AirTable / Netlify Forms / Getform / FormKeep

### 评论工具

- walinejs / Staticman / Disqus

### 商品交易

- Shopify / Snipcart / Commerce Layer

### 搜索服务

- Algolia / fuse.js / Lunr.js

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# DEPLOY

<br/>

- Netlify，2020 年 5300 万 C 轮
- Vercel，2021 年 1.5 亿美金 D 轮，估值 25 亿美金
- Github Pages
- Fly.io
- Digital Ocean
- Azure Static Web Apps

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 简单总结

<br/>

- 利用一系列工具组合，快速构建和部署自己的网站。
- 在国外是一个很大的市场，在国内基本不存在这些场景，国内同样的场景是给每个小程序平台写小程序，各平台有自己的部署、函数、存储。。
- 国外社区这种整体架构分解、细分领域发力、灵活重组、生态上互相支持，共赢且推动社区向同一个方向发展的做法值得深思。
- 很多公司和产品以 Jamstack 为核心理念推动和宣导。

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 示例

<br/>

现在，开发一个轻量级的前端应用，可以存取数据，运行简单的服务端，存储数据，cdn 访问等。

- 界面搭建，可以使用 hugo/Gatsby/vuepress 等无代码框架
- 也可以使用 Nextjs 等开发界面。
- cdn 托管：将应用部署到 vercel，直接分发到全球的端点网络。
- 逻辑开发：使用 Nextjs 开发轻量级的 serverless 函数，部署到 vercel 之后，无缝集成 vercel serverless。
- 部署：从 github 开始，无缝导入 vercel/netlify/hehuko 等平台，自动集成打包分发。
- 存储：使用 prisma data proxy 为 serverless 提供数据库服务（可解决连接数问题）
- 数据管理：使用 prisma studio web ui 直接管理或者使用 prisma platform 管理
- 数据访问：使用 prisma orm 在代码中快速访问数据
- 数据库服务：使用 heruko 云原生 postgres 服务，或者使用其他云原生 数据库服务，搭配 prisma 使用。
- 接口：使用 graphql 配合 prisma 和 nextjs，快速输出标准接口服务

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 四 浏览器计算能力

- 多线程（上一代）
- WebGL（上一代）
- WebAssembly
- WebCodecs
- WebGPU

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 上一代技术

### Web Workers

- 不阻塞主线程的计算进程，不可操作 UI
- 工程化困难，使用比较别扭，和其他 Native 语言操作多线程的体验差距比较大
- 初始化和传输数据开销比较大，非必要不要用，可能会让应用变得更慢

### WebGL

- 在我们的地理可视化产品中，一个界面上渲染 几十万个可交互的点不卡顿基本没有问题，所以 WebGL 的性能渲染普通的图形是够用的。
- 始于 2006 年，2011 年 WebGL 1.0 标准，2017 年发布 2.0 标准。
- Apple 直到 2020 年才支持 WebGL 2.0。
- 几乎现在所有的操作系统都不再把 OpenGL 作为首要支持。
- WebGL 至今不可以做并行计算。

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

## WebAssembly

- 是一种低级的类汇编语言，具有紧凑的二进制格式，可以接近原生的性能运行，并为诸如 C / C ++等语言提供一个编译目标，以便它们可以在 Web 上运行
- 所以可以用来做音视频编解码（例如将 FFmpeg 编译到 wasm，然后运行于浏览器中，然而现实情况是需要对 FFmpeg 大量裁剪，并且因为逻辑比较重，效果并不理想）
- 可以用来做科学计算并行计算（WebAssembly SIMD 是最新的 Wasm 技术，它可以实现数据层面的并行处理）
- 可以用来做图形处理等（如 figma 大量使用 wasm 处理设计稿的渲染和特效等）
- 支持诸多语言编译，c/c++、rust、kotlin、swift、c# 等

[Google Meet 中使用 wasm 来实现高效的背景实时替换](https://cloud.tencent.com/developer/article/1745435)
[Chrome 91 支持 WebAssembly SIMD，加速 Web 在 AI 等领域的应用](https://mp.weixin.qq.com/s/P0opB_IMHoAy7PpJH0t-4A)

## WebCodecs

- 可使用底层硬件加速编解码
- wasm 实现编解码过程太复杂，使用复杂

[WebCodecs 对音视频进行编码解码](https://juejin.cn/post/6885482349098860558)

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# WebGPU

此 demo 只能在 Chrome Canary 中开启 WebGPU 后使用

<iframe src="https://playground.babylonjs.com/?webgpu#YX6IB8#36" style="width:100%;height:40vh;"/>

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# WebGPU

<br/>

- [硬件级] WebGPU 是一个精确的图形 API，它完全开放了整个显卡能力，你要向显卡发送命令去控制显卡，它不再是画东西的一个库，而是一个利用 GPU 的库。
- [跨平台] WebGPU 就像一个 HAL 硬件抽象层一样，我只要对应这套标准，未来不仅可以在网页运行，甚至也可以在嵌入式、在服务器运行
- [通用计算] WebCPU 终于开始支持 GPU Compute Shader，并且是把 GPU 通用计算作为首要支持
- [着色器] 新的着色器语言 WGSL，支持面向对象编程
- [性能差距] babylonjs 示例，性能差距 6 倍以上。

<br/>

[从 WebGL 到 WebGPU，网页图形的全新时代](https://mp.weixin.qq.com/s/4LfaNHP77s9n9SghucYoaA)

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 五 浏览器系统能力

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 浏览器系统能力

- 音视频。MediaStream(音视频流) / Media Source Extensions（程序媒体流输入）/ MediaStream Recording(流捕获) / MediaStream Image Capture / Capabilities（编解码探测）/ Web Audio API（音频处理、分析、效果等） / Web Speech API（语音识别和合成） / MIDI API（音乐合成）/ WebCodecs （音视频编解码）/ WebVTT（字幕）
- 桌面。Screen Capture（屏幕捕捉）/ Picture-in-Picture（画中画） / EyeDropper(拾色) / Notifications / Page Visibility / Screen Wake Lock （阻止休眠） / VisualViewport（可见窗口探测）/ Window Controls Overlay（控制标题栏）
- 存储。File System Access API / IndexedDB（大数据存储） /
- 网络。Streams API（按位读取写入）/ WebRTC API（点对点通信）
- 外设。 WebAR / WebXR / GamePad / Battery Status API / Bluetooth API / Presentation API（演示屏幕控制）/
- 传感器。Sensor（三轴传感器）/ Geolocation （位置） / Screen Orientation （屏幕旋转） / Vibration（震动传感器）
- 脱机。Service Worker API(离线) / Background Fetch API（页面关闭后仍可请求数据） / Background Synchronization（背景同步资源） /
- 虚拟设备。Payment Request API（信用卡支付）/ Clipboard API / Pointer Lock（鼠标锁定）
- 内容。Encoding API / Intersection Observer API(内容探测) /
- 性能探测。Performance API（延时探测） / Navigation Timing（页面跳转性能探测） / Long Tasks API（高损耗探测）/ Resource Timing（资源加载探测）

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 注意点

<br/>

- 部分功能需要 https 环境，特别是涉及到隐私和安全的。
- 部分功能需要用户确认，通过 permissions api 管理。
- 以上提到的大部分功能都在 90 之前版本可用，极少数是最新的规范

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# Google Meeting

<video src="/11.mp4" controls style="height:70%;border-radius:5px;" autoplay />

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# 五 移动端

## flutter

- [flutter 2.8 更新](https://medium.com/flutter/announcing-flutter-2-8-31d2cb7e19f5)
- 支持 Mobile / Web / Desktop（windows/linux/mac） / Embedded App
- 开始集成越来越多 Google 自己的服务（和浏览器一个套路）
- 发布 flame 游戏框架

## iOS

- Xcode Cloud，持续集成，在线构建和分发
- iPad Swift Playground 可以直接编译成 app
- Live Text / SharePlay / RealityKit / ARKit /

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

  background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>

---

# 六 Web3

- web1 浏览，web2 发布，web3 拥有。
- web3.js ethers.js 智能合约 hardhat typechain web3modal 等等
- 开发体验类似于 serverless，可以把区块链理解成一个分布式的虚拟机平台和状态存储平台。
- 依托与智能合约实现数据逻辑，比较大的挑战是单向状态机和普通应用间的差异，业务逻辑的架构设计完全不同。
- 对新人来说，晦涩的概念比较多，很多金融的概念，但是实际上技术和开发体验是比较简单的。
- 感兴趣的同学可以加我 ,或者直接加 telegram: https://t.me/+versCrAb2lM1ZTI1

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: right -120% top -100%, left -500px top -400px, left 50% bottom -40%, right -50% bottom -30%, left -60% bottom -30%;
}

  </style>

---

# More

欢迎 PR 补充内容

[GitHub 链接](https://github.com/yu-tou/web-front-end-technology-forward-share-slide)

<img src="/weixin.jpeg" style="width:300px"/>

<style>
.slidev-layout {
  background: url(/bg-1.svg),
    url(/bg-2.svg),
    url(/bg-3.svg),url(/bg-4.svg),url(/bg-5.svg);
  background-repeat: no-repeat, no-repeat, no-repeat, no-repeat, no-repeat;
  background-size: 70% 70%, 120% 120%, 50% 50%, 50% 50%, 50% 50%;

background-position: left -120% top -50%, right -450px top -350px, right -30% bottom -20%, left 50% bottom -40%, left -60% bottom -30%;
}

  </style>
