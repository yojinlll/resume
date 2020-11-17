---
pageClass: home-page
# some data for the components

name: 劳业锦
profile: /profile1.jpg

# socials:
#   - title: github
#     icon: "/icons/github.svg"
#     link: https://github.com/yojinlll
  # - title: linkedin
  #   icon: "/icons/linkedin-mono.svg"
  #   link: https://www.linkedin.com
  # - title: instagram
  #   icon: "/icons/instagram-mono.svg"
  #   link: https://www.instagram.com

# cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: 13728906723
email: yojin0623@foxmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## 技术栈

- 熟练使用 **Vue / React**

- 熟练使用 **HTML5** 及 **CSS3** 常用语法，能够高度还原 UI 视觉稿

- 熟悉 **JavaScript** 语言，熟练使用 **ES6** 常用语法

- 了解浏览器渲染过程及前端常用的性能优化策略

- 熟悉 PC 与移动端的开发与适配，了解微信小程序开发

- 掌握常用的 **Git** 命令

<!-- ## News

- [Sept 1991] Attended Hogwarts
- [July 1980] Born in Godric's Hollow, West Country, England, Great Britain -->

## 公司项目


<!-- [→ more](/projects/) -->

<ProjectCard image="/projects/bapbet.jpg" hideBorder=true>

  **BAPBET**  - (Meteor/Vue/Koa)

  BAPBET 是基于区块链公平技术的跨链娱乐平台。 它支持 EOS，TRX，ETH，USDT，BTC 和 其他加密货币。 当前游戏包括百家乐，德州扑克，骰子，骰宝，幸运777，二十一点，斗牛等。Sportbet，Live Casion 也将陆续推出。

  - BAPBET 项目由 Meteor 全栈框架开发，前端使用 Vue，后端使用 Koa。
  - 独立负责该项目，按设计图稿完成需求和适配移动端。
  - 项目中使用 Bootstrap UI， 结合需求对组件进行二次封装
  - 对接后端数据，合理使用本地缓存对内容显示进行优化。
  - 同时负责 BAPBET 后台管理的前端开发。
  - 在活动需求赶进度时，也有根据需求对后端接口进行细微调整。
  
  [[链接](https://www.bap.bet/home)]
  [[相关](https://www.dapp.com/app/bapbet)]

</ProjectCard>

## 个人项目

<ProjectCard image="/projects/miro-ui.jpg" hideBorder=true>

  **Miro UI** 
  
  - React/Webpack
  
  使用 React 完成常见前端组件的开发，无其他依赖，并使用 Jest 编写了部分单元测试，并且在 Circle CI 上进行自动化测试。

  [[链接](https://yojinlll.github.io/miro-react/docs#/guide)]

</ProjectCard>

<ProjectCard image="/projects/miro-note.jpg" hideBorder=true>

  **Miro Note**

  - React/Nextjs/Webpack/Typescript
  - Typeorm/PostgreSQL
  
  使用 Nextjs 全栈框架开发的记事本应用，使用 Webpack 进行项目打包，并通过 Docker 和 Bash 脚本完成一键部署。 该项目主要是对 Nodejs 服务端渲染这方面的一次应用实践，部署在阿里云。

  [[链接](http://39.100.54.22:3000/)]

</ProjectCard>


## 工作经验

- **深圳猎语科技有限公司** &nbsp;&nbsp; 2019/03 - 2020/09

## 教育经历

- **深圳职业技术学院** <br/>

<!-- ## Awards & Honors

### Contests

- First place in **The Hogwarts House Cup** -->


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
    font-size: 1.4rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      margin-right 12px
      img
        max-width 160px
        max-height 120px
        width 160px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px
          max-height 150px

</style>
