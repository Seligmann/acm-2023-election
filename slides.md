---
# try also 'default' to start simple
# theme: default 
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1557683311-eac922347aa1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2029&q=80
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Zachary Seligman

For Projects Officer

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# About me

Second year Computer Science student and back-end software engineer with experience in web development 
and machine learning, and a strong personal interest in projects surrounding media

### Hobbies 

- 🖥️ Software engineering - Twitch, Twitter, YouTube, Discord
- 🎮 Video games - Minecraft, Factorio, League of Legends, Rhythm Games
- 🎸 Playing the guitar

### Skills

- ⌨️ **Languages** - TypeScript, Rust, Java, C++, Python, and more...
- 💻 **Frameworks and Libraries** - React, Express.js, Next.js, PyTorch, Tensorflow, OpenCV
- 💽 **Databases** - PostgreSQL, MongoDB, Clickhouse, SQLite, and more...
- 🖱 **Devops** - Railway, Hetzner Cloud, Vercel, Cloudflare Pages, NameCheap, and more...
- 🏆 **Competitive Programming** - ICPC contender for almost 2 years, along with many problems solved in Codeforces and Leetcode

<br>
<br>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
transition: slide-up
---

# Goals 

### Portal Metrics Dashboard
Currently, there isn't a good view on what the general member is interested in when they join ACM.
Because of the Portal project, we keep track of event attendance, which members are in which sub-organizations, as well
as other info, but this information is not aggregated into any useful information.

If elected, I plan on implementing an interface in Portal to view popularity of events, attendance in sub-orgs, and other
metrics, all over time.

### Portal + Discord integration

Part of tracking the interest in certain events lead by ACM is looking into Discord activity. Discord is a platform
whose API and documentation I have familiarity with, and I have also been an active contributor this past semester for
the Portal project.

If elected, I'd be able to leverage engagement towards events on Discord, and add more robustness to the view of what
our ACM members want.

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
---
transition: slide-up
---

# Collaboration and Help

### Contribution to in-house software
Getting integrated into working on projects such as Portal doesn't feel streamlined as a non-officer.

If all of this in-house software is to be not only contributed to, but even maintained in the future, more communication
around projects must be clearly visible to the public.

### Workshops and learning
There are too many people who seemingly have interest in working on projects who are not tended to. 

Full-stack workshops hosted this semester are an amazing way to get people over the initial hump in software development,
and more workshops like these, as well as more spontaneous one-on-one help, should be readily available.


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
---
transition: slide-up
---

# Contact/Socials

- **Email** - zachary.a.seligman@gmail.com
- **Discord** - Zelig#7372
- **Linkedin** - https://www.linkedin.com/in/zachary-seligman-6525b1170/
- **Github** - https://github.com/Seligmann

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
