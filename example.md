---
theme: ./
colorSchema: dark
layout: cover
background: '/assets/images/shape.png'
---

# Slidev Theme Capgemini

A Capgemini template for developers

<div class="uppercase text-sm tracking-widest">
Yohann Ciurlik
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="/assets/images/logo.png" class="h-8">
  <div class="ml-3 flex flex-col text-left">
        <div><b>Digital Customer eXperience</b></div>
    <div class="text-sm opacity-50">23 Juillet 2021</div>
  </div>
</div>

---
layout: cover
background: '/assets/images/cover.jpg'
---

# Slidev Theme Capgemini

Another cover type

<div class="uppercase text-sm tracking-widest">
Yohann Ciurlik
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="/assets/images/logo.png" class="h-8">
  <div class="ml-3 flex flex-col text-left">
        <div><b>Digital Customer eXperience</b></div>
    <div class="text-sm opacity-50">23 Juillet 2021</div>
  </div>
</div>

---
layout: image-right
image: '/assets/images/cover.jpg'
---

# Slidev Theme Capgemini

Yet another cover type

<div class="uppercase text-sm tracking-widest">
Yohann Ciurlik
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="/assets/images/logo.png" class="h-8">
  <div class="ml-3 flex flex-col text-left">
        <div><b>Digital Customer eXperience</b></div>
    <div class="text-sm opacity-50">23 Juillet 2021</div>
  </div>
</div>

---
layout: 'intro'
---

# Yohann Ciurlik

<div class="leading-8 opacity-80">
Managing Solutions Architect.<br>
Web, Mobile & API specialist.<br>
Involved in open source & security.<br>
</div>

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/spawnrider" target="_blank">spawnrider</a></div>
  <ri-twitter-line class="opacity-50"/>
  <div><a href="https://twitter.com/spawnrider" target="_blank">spawnrider</a></div>
  <ri-user-3-line class="opacity-50"/>
  <div><a href="https://ciurlik.com" target="_blank">ciurlik.com</a></div>
</div>

<img src="https://miro.medium.com/max/3150/2*wgN90FVfj1fSCjCU738doQ.jpeg" class="rounded-full w-40 abs-tr mt-16 mr-12"/>

---
layout: image-right
image: /assets/images/building.jpg
---


# Agenda

Slide Subtitle

* Slide bullet text
  * Slide bullet text
  * Slide bullet text
* Slide bullet text
* Slide bullet text

---

# What is Slidev?

Slidev is a slides maker and presenter designed for developers, consist of the following features

- 📝 **Text-based** - focus on the content with Markdown, and then style them later
- 🎨 **Themable** - theme can be shared and used with npm packages
- 🧑‍💻 **Developer Friendly** - code highlighting, live coding with autocompletion
- 🤹 **Interactive** - embedding Vue components to enhance your expressions
- 🎥 **Recording** - built-in recording and camera view
- 📤 **Portable** - export into PDF, PNGs, or even a hostable SPA
- 🛠 **Hackable** - anything possible on a webpage

<br>
<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)


---

# Navigation

Hover on the bottom-left corner to see the navigation's controls panel

### Keyboard Shortcuts

|     |     |
| --- | --- |
| <kbd>space</kbd> / <kbd>tab</kbd> / <kbd>right</kbd> | next animation or slide |
| <kbd>left</kbd>  / <kbd>shift</kbd><kbd>space</kbd> | previous animation or slide |
| <kbd>up</kbd> | previous slide |
| <kbd>down</kbd> | next slide |

---
layout: image-right
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
---

# Code

Use code snippets and get the highlighting directly!

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = {...user, ...update}  
  saveUser(id, newUser)
}
```

---
layout: center
class: "text-center"
---

# Learn More

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)

---
layout: center
class: 'text-center pb-5 :'
---

# Thank You!

Slides can be found on [xxx](https://xxx)