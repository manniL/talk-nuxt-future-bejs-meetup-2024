---
theme: ./theme
title: "Nuxt 3 - The Present and the Future"
website: lichter.io
handle: TheAlexLichter
favicon: https://lichter.io/img/me@2x.jpg
highlighter: shiki
lineNumbers: true
layout: intro
transition: fade
---


---
layout: intro
---


# <logos-nuxt-icon/> Nuxt <span class="text-[#00DC82]">3?</span>

## The Present and the Future

<br><br>

### BEL Vue x BeJS - Meetup 04/2024

---
layout: two-cols
heading: About me
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
  <img class="w-75 rounded-full" src="https://lichter.io/img/me@2x.webp" />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>
<VClicks class="space-y-2 mt-10 text-xl h-full">

* <mdi-account-check class="dark:text-green-100 text-green-700" /> **Web Engineering Consultant**
* <mdi-microphone /> Speaker &bull; Instructor &bull; Podcast Host
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /><mdi-youtube class="text-red-500" /><mdi-twitch class="text-purple-700" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</VClicks>
</template>

---
layout: intro
---

# <logos-nuxt-icon/> Nuxt <span class="text-[#00DC82]">3</span>

---
layout: intro
---

# <logos-nuxt-icon/> Nuxt <span class="text-[#00DC82]">4</span>

<VClicks depth="2">

* Was planned for Q1, moved to Q2 because other things had to ship first
* New goal: "Nuxt v4 on or before June 14"
  * Depends on various UnJS major versions (e.g. Nitro)
* 6 months support + bug fixes for Nuxt v3 from that point on

</VClicks>

---
layout: intro
---

# <span class="text-[#00DC82]">Features</span> in Nuxt <span class="text-[#00DC82]">4</span>

<VClicks>

## Which big features are coming?

</VClicks>

---
layout: intro
---

# NONE

---

# NONE


* Amazing features in every minor release

<VClicks>

* Major release = Breaking changes

</VClicks>

---
layout: intro
---

# Breaking Changes

<img class="mx-auto" src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExd3hvdG1jaWFoYW81anMyOGJpZjZmOGl4OTk3eHA4N2Zuc3loNzgycSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l2Je2ifGlRZEWDbb2/giphy.gif" v-click>

---
layout: intro
---

# Who is still traumatized by

<VClicks>

## Vue 2 -> Vue 3

</VClicks>

<VClicks>

## Nuxt 2 -> Nuxt 3

</VClicks>

<style>
h2 {
  @apply !text-4xl !mt-8;
}
</style>

---
layout: intro
---

<img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExeW8zbDlseGF2czd1c2YwZmh4Nzc3bTR2a3J0cXlhcjd0OGh3Nm50NSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/PMUooKtzGNjsPXkQUJ/giphy.gif" class="mx-auto">

---

# Breaking Changes


<VClicks depth="2">

* So, what should we expect?
* A migration like Nuxt 2 to Nuxt 3?

</VClicks>

---
preload: false
---

<img v-motion :initial="{ y: 500 }" :enter="{ y:0, transition: { duration: 1000 } }" src="/angry.png" />

---

# No! Don't worry!

<VClicks depth="2">

* A [list](https://github.com/nuxt/nuxt/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A4.x) of smaller breaking changes
  * Non-exhaustive
* More to come
* But in no way comparable to version three

</VClicks>

---
layout: intro
---

# How can the team help?

---

# How can the team help?

<VClicks>

* We will provide an extensive migration guide
* We plan on providing code mods / a migration wizard
* `future` flag to enable breaking changes before they'll happen

</VClicks>

---
layout: intro
---

# Why Nuxt 3 was "different"

---

# Why Nuxt 3 was "different"

<VClicks>

* TS rewrite
* New internal architecture
* Fresh server engine
* Switching from Webpack 4 to Vite (while still supporting 5)
* Switching from Vue 2 to Vue 3
* Dealing with the Composition API
* Pushing the ecosystem forward

</VClicks>

---
layout: intro
---

# Nuxt 4 = None of these kind of changes

---

# Nuxt 4 = None of these kind of changes

<VClicks depth="2">

* The chance for the team to introduce breaking changes
  * e.g. to remove legacy code
  * or to enable sensible defaults
  * And so on

</VClicks>

---
layout: intro
---

# Let's <span class="underline"> **not** </span> make majors a **marketing thing**

---
layout: intro
preload: false
---

<img v-motion class="mt-14" :initial="{ y: 500 }" :enter="{ y:0, transition: { duration: 1000 } }" src="/happy.png" />


---
layout: intro
---

# <span class="text-[#00DC82]">More</span> Features

---

# <span class="text-[#00DC82]">More</span> Features

<VClicks depth="3">

* More work on experimental features:
  * Server Components
  * Typed Pages
  * Nitro experimentals
    * Tasks
    * DB0
    * crossws
  * and so on

</VClicks>

---
layout: intro
---

# <span class="text-[#00DC82]">Upcoming</span> Features (core)

---

# <span class="text-[#00DC82]">Upcoming</span> Features (core)

<VClicks depth="2">

* `onPreHydrate`
* Built-in build cache
* Make Multi App Support possible
* Various other thing I can't name here ;)

</VClicks>

---
layout: intro
---

# <span class="text-[#00DC82]">Upcoming</span> Features (non-core)

---

# <span class="text-[#00DC82]">Upcoming</span> Features (non-core)

<VClicks depth="2">

* Nuxt Module for Third Party Handling
* Nuxt Fonts Module 
  * Wait, this is already out!
* Perf Hints Module
* a11y Module
* Render Markdown in Nuxt straight away
  * Wait, this is also already out!

</VClicks>

---
layout: intro
---

# Anything <span class="text-[#00DC82]">else</span> you want to see?


---
layout: intro
---


# One more thing...


<div class="justify-around flex">
<VClicks>

<div>
<img src="https://michaelnthiessen.com/profile.jpg" alt="Michael Thiessen" class="rounded-full w-32 h-32 mx-auto" />
<h2 class="mt-4">Michael Thiessen</h2>
</div>

<div>
<img src="https://lichter.io/img/me@2x.jpg" alt="Alexander Lichter" class="rounded-full w-32 h-32 mx-auto" />
<h2 class="mt-4">Alexander Lichter</h2>
</div>

</VClicks>
</div>


---
preload: false
---

<div class="justify-center items-center flex w-full h-full">
  <div class="luminance py-4">
  DejaVue
  </div>
</div>

<style>
.luminance {
   background: 50% 100% / 50% 50% no-repeat
              radial-gradient(ellipse at bottom, #fff, transparent, transparent);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-size: 10vw;
  font-family: "Source Sans Pro", sans-serif;
  animation: reveal 3000ms ease-in-out forwards 200ms,
             glow 2500ms linear infinite 2000ms;

  @keyframes reveal {
    80%{
      letter-spacing: 8px;
    }
    100% {
      background-size: 300% 300%;
    }
  }
  @keyframes glow {
    40% {
      text-shadow: 0 0 8px #fff;
    }
  }
}
</style>

---
layout: intro
---

<div class="justify-center items-center">
<div class="font-src text-6xl py-4" style="text-shadow: 0 0 200px #fff;">DejaVue</div>

## The Vue Podcast to Remember

<Qrcode url="https://dejavue.fm?ref=belvue-meetup-04-24" class="mt-8 mx-auto" />

# `https://dejavue.fm`

</div>

<style>
h1 {
  @apply !text-4xl !mt-16;
}

h2 {
  @apply !text-xl;
}

.font-src {
  font-family: "Source Sans Pro", sans-serif;
}
</style>

---
layout: intro
---

# Thanks a lot to my sponsors!
<img src="https://raw.githubusercontent.com/manniL/static/main/sponsors.svg" class="h-80 mx-auto" alt="My GitHub sponsors">

---
layout: two-cols
heading: Thank you for your attention!
---

<template v-slot:default>
<div class="flex flex-col justify-center items-center h-full">
<img
  class="w-75 rounded-full"
  src="https://lichter.io/img/me@2x.webp"
  />
  <h2 class="mt-4">Alexander Lichter</h2>
</div>
</template>

<template v-slot:right>

* <mdi-account-check class="dark:text-green-100 text-green-700" /> **Web Engineering Consultant**
* <mdi-microphone /> Speaker & Instructor
* <logos-nuxt-icon /> Nuxt.js Team
* <mdi-twitter class="text-blue-400" /><mdi-youtube class="text-red-500" /><mdi-twitch class="text-purple-700" /> @TheAlexLichter
* <mdi-web /> [https://lichter.io](https://lichter.io)
* <mdi-github /> [manniL](https://github.com/manniL)

</template>

<style>
  ul {
    @apply space-y-2 mt-10 text-xl h-full;
  }
</style>