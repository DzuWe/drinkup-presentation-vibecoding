---
# You can also start simply with 'default'
theme: catppuccin-mocha
# some information about your slides (markdown enabled)
title: невайбкодинг
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: fade
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev

layout: center
---

# Вайбовый кодинг

<br>
<br>
<div class="flex flex-items-center justify-center gap-3 text-green-300 text-2xl">
<svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" viewBox="0 0 32 32" fill="none">
        <circle cx="16" cy="16" r="14" fill="url(#paint0_linear_87_7225)"/>
        <path d="M22.9866 10.2088C23.1112 9.40332 22.3454 8.76755 21.6292 9.082L7.36482 15.3448C6.85123 15.5703 6.8888 16.3483 7.42147 16.5179L10.3631 17.4547C10.9246 17.6335 11.5325 17.541 12.0228 17.2023L18.655 12.6203C18.855 12.4821 19.073 12.7665 18.9021 12.9426L14.1281 17.8646C13.665 18.3421 13.7569 19.1512 14.314 19.5005L19.659 22.8523C20.2585 23.2282 21.0297 22.8506 21.1418 22.1261L22.9866 10.2088Z" fill="white"/>
        <defs>
            <linearGradient id="paint0_linear_87_7225" x1="16" y1="2" x2="16" y2="30" gradientUnits="userSpaceOnUse">
                <stop stop-color="#37BBFE"/>
                <stop offset="1" stop-color="#007DBB"/>
            </linearGradient>
        </defs>
    </svg>
    dzu_we
</div>

---
layout: image-left
image: /photo_2025-02-09_13-08-50.jpg
---

# О себе

<br>

- 👤 **Зовут Дзюба Дима** 👤
- 🟥 **Работаю в MWS** 🟥
- 🌄 **Пилю фронтенд на Vue** 🌄
- 🧑‍💻 **Nvim onelove** 🧑‍💻

<v-click>

- ⚽ **Это не мой родственник распространяет интимные видео** ⚽

</v-click>

---
layout: two-cols
---

# О чем буду говорить?
<br v-for="n of 2">

- О больших языковых моделях?

<v-clicks>

- О промпт инжениринге, как перспективной профессии?
- Об инструментах для работы с ИИ?
- О том как ИИ заменит разработчиков?

</v-clicks>

::right::

<div class="grid h-100% place-items-center">
   <img v-if="$clicks === 0" style="scale: 0.5" src="/clown1.webp"/>
   <img v-if="$clicks === 1" style="scale: 1" src="/clown2.webp"/>
   <img v-if="$clicks === 2" style="scale: 1.5" src="/clown3.webp"/>
   <img v-if="$clicks === 3" style="scale: 2" src="/clown4.webp"/>
</div>

<style>
img {
    border-radius: 12px;
    width: 200px;
}
</style>

---
layout: center
---

<img src="/NO-gif.webp" class="m-auto h-80" />

# НЕТ!

<style>
h1{text-align: center; padding-top: 2rem}
img {border-radius: 12px}
</style>

---
layout: two-cols
---

# А говорить буду про:

- Недооцененные штуки
<v-clicks>

- Гиковые гаджеты
- Разные программы

</v-clicks>

<v-click at="4">

- Ricing
- и другие полезные штуки, как сделать кодинг вайбовым

</v-click>

::right::

<img src="/keyboard.jpg"  v-if="$clicks === 0" />
<img src="/geek.jpg"  v-click="[1, 2]" />
<img src="/vim.jpg"  v-click="[2, 3]" />
<h3 class="joke" v-click="[3, 4]"><strong>ШУТКА</strong>,<br> сегодня без вима</h3>
<img src="/ricing.png"  v-click="4" />

<style>
img, .joke {
    max-width: 300px;
    position: absolute;
    top: 50%;
    right: 3em;
    transform: translateY(-50%);
}
img {
    border-radius: 1rem;
}
</style>

---
layout: two-cols
---

# Что такое Vibecoding?
<br />
<br />

<div class="info">
ℹ️ (в кратце)
<br> программирование значительного кода продукта используя только естественный язык и llm агенты
</div>

::right::

<video src="/vibox.mp4" autoplay loop muted />

<style>
   .info {
       padding-left: 1rem;
       border-left: 3px solid var(--cyan);
   }
   video {
       border-radius: 10px;
       margin: auto;
       width: 260px;
   }
</style>

---
layout: fact
---

## <code class="wrong">Vibecoding</code> !== <code>Вайбовый кодинг</code>

<style>
.wrong{
    color: var(--red) !important;
}
</style>

---
layout: fact
---

# **Вайбовый кодинг**

<style>
h1 {
    font-size: 7em !important;
}
</style>

---
layout: image
image: /more-monitors.jpg
---

---
layout: image
image: /trent-van-gaming-setup-vanlife-2470197836.jpg
---

---
layout: image
image: /my-deck.jpg
---
<span class="absolute top-57 text-green-700 font-bold shadow left-42 rotate-350 bg-white b-rd">БЭМ</span>

---
layout: image
class: pt-100
image: /true-vibe.jpg
---

<h1 class="floating bottom-10 right-4"><strong><i>vibe</i></strong> - атмосфера вокруг, общее состояние</h1>

---
layout: quote
class: grid place-items-center bg-black
---

<h1 class="text-center">Погнали разбираться</h1>
<img class="mx-auto b-rd-8" src="/hack.gif" />

---
layout: fact
---

# **Железо** 🍻 <span style="color: var(--green)">Софт</span>

---
layout: image
class: grid place-items-center
image: /iron_texture1044-669289013.jpg
---

<h1 class="b-rd-4 p-8" style="background: #11111D99; font-size: 80px; color: var(--orange)" >
    Железо
</h1>

---
layout: fact
---

## Про цены:
# 🍺 = 500р

---
src: ./pages/hardware/mouses.md
---

---
src: ./pages/hardware/touchpads.md
---

---
src: ./pages/hardware/trackball.md
---

---
src: ./pages/hardware/keyboards.md
---

---
src: ./pages/hardware/bracket.md
---

---
src: ./pages/hardware/custom-things.md
---

---
src: ./pages/hardware/other-harware.md
---

---
layout: image
class: grid place-items-center bg-black
backgroundSize: 40em
image: /matrix.gif
---

<h1 class="b-rd-4 p-8" style="background: #11111D99; font-size: 80px; color: var(--green)" >
    Софт
</h1>

---
src: ./pages/software/tilling.md
---

---
src: ./pages/software/virtual-pointers.md
---

---
src: ./pages/software/tui.md
---

---
layout: image-left
image: /Themes/preview.webp
---

# Цветовые схемы
<br>

- **catppuccin** (onelove)
- tokyonight
- gruvbox
- onedark
- dracula
- и тд

---
layout: two-cols
---

# Cобираем все в кучу
<br>
<br>

<v-clicks>

- Конфигурируем Тайловый WM
- Устанавливаем всякие TUI программки
- Накидываем полезных виджетов
- Настраиваем IDE под себя
- Льем одну тему во все установленное
- тудым сюдым

</v-clicks>

::right::

<v-click>
    <div class="boom h-80 grid place-items-center mt-20 font-size-20 ">
        <span class="ricing">
        RICING
       </span>
    </div>
</v-click>

<style>
.ricing {
    background: linear-gradient(to right, var(--red), var(--green), var(--yellow));
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}
</style>

---
src: ./pages/software/ricing.md
---

---
layout: fact
---

# А дальше что?

---
src: ./pages/software/cool-programs.md
---


# Становимся кулхакерами
Берем пиво, натягиваем худи и идем при помощи программирования решать стандартные задачи

### Word
`latex/typst` с `pandoc` конвертером

### Powerpoint
`slidev`, `reveal.js`, `presenterm`, `slides`

### Video Editors
`remotion`, `revideo`

---
layout: end
---
<div>

## Короче, выбирай свою сторону!
<div class="images">
    <img class="nerd" src="/nerd.jpg" />
    <img class="hacker" src="/hackerman.png" />
</div>

<v-click>

### и куй свое вайбовое окружение
</v-click>
    
</div>

<style>
.images {
    margin-top: 36px;
    margin-bottom: 36px;
    display: flex;
    gap: 2em;

img {
    width: 250px;
    border-radius: 12px;
}
}
</style>


---
layout: end
---

<div class="grid">
<div>

# Спасибо за внимание
#### вещал Дима
#### да прибудет с вами **ПИИИВО**
</div>

<div class="flex self-end">
        <img src="/presa.png" />
        <label class="floating">ПРЕЗА</label>
</div>

</div>

<style>
* {
    text-align: left;
}
.floating {
    top: 250px;
    right: 195px;
    font-size: 36px;
    font-weight: bold;
}
.grid {
    display: grid;
    gap: 20px;
    place-items: center;
    grid-template-columns: repeat(2,  1fr);
}
</style>

