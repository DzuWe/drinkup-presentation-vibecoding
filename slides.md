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

- О промпт инженерах?
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
- Полезные программы

</v-clicks>

<v-click at="4">

- Ricing
- и другие полезные штуки как сделать кодинг комфортным

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

# Vibecoding
<br />
<br />

<div class="info">
ℹ️ (в кратце)
<br> программирование значительного кода продукта используя только естественный язык и llm агенты
</div>

::right::

<video src="./public/vibox.mp4" autoplay loop muted />

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
image: ./public/trent-van-gaming-setup-vanlife-2470197836.jpg
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
src: ./pages/tilling.md
---

---
src: ./pages/virtual-pointers.md
---

---

# TUI приложения

<br>

<div class="info">

ℹ️ 
<br> **TUI** - text user interface, terminal user interface

<br> GUI в терминальчике короче
</div>

<style>
   .info {
       padding-left: 1rem;
       border-left: 3px solid var(--cyan);
   }
</style>

---
class: grid grid-cols-3 gap-5
---

<h1 class="grid-col-span-3">TUI приложения (их миллионы)</h1>
<div>
    <img src="/tui/queue.BYnoUff__uRxjq.webp"/>
    <label>Music player (rmpc)</label>
</div>

<div>
    <img src="/tui/11fc1cbd-b255-4d03-871c-b3352e992593.gif"/>
    <label>Telegramm client (tgt)</label>
</div>

<div>
    <img class="h-38 mx-a" src="/tui/sunflower-term.png"/>
    <label>Image/video viewer (timg)</label>
</div>


<style>
img {
    margin-bottom: 12px;
}

h1 ~ div {
    text-align: center;
}

label {
    text-align: middle;
    font-size: 12px;
}
</style>

---
layout: image-right
image: /matrix.gif
---

# TUI приложения
<br>

#### Особи:

<v-click>
    <div class="mt-10 w-60 fit-content text-center">
        <img class="h-60 mb-8" src="/tui/qr-code.png" />
        <label > git tui-awesome </label>
    </div>
</v-click>

<style>
</style>

---
layout: image-left
image: /Themes/preview.webp
---

# Цветовые схемы
<br>

#### Их миллион:
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
- Разные TUI программки
- Накидываем полезных виджетов
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

<div class="grid gap-3">
<h1 class="grid-col-span-2">Ricing</h1>

<div class="info mt-20">

ℹ️ 
<br> **Ricing** - готовка чего либо
<br> *Сленговое* - глубокая кастомизация
</div>
<video  class="w-120 mt-8 b-rd-8 mx-a" loop autoplay src="/ricing/m2-res_480p.mp4" />

</div>

<style>
   .grid {
       grid-template-columns: 0.6fr 1fr;
   }

   .info {
       height: 100px;
       padding-left: 1rem;
       border-left: 3px solid var(--cyan);
   }
</style>

---
class: grid grid-cols-2 grid-rows gap-12
---

<h1 class="grid-col-span-2">Ricing (примеры)</h1>

<img  src="/ricing/7fcf6711c8ae6192c01ff0d60bf67216.png"/>
<img src="/ricing/16b3dd673f581f021ce2ccbd705d09cf.png"/>
<img src="/ricing/246a81b266d0b9ba7f83349758ab89b8.png"/>
<img src="/ricing/03a7295fa0e9e58a1a5bbd8a699ef8b9.png"/>

<style>
img {
    margin: auto;
    height: 100%;
}
.grid {
    grid-template-rows: 20px  180px 180px;
}
</style>

---
layout: fact
---

# А дальше что?

---

# Становимся кулхакерами
Натягивай худи и иди заменять стандартные приложения на ide

### Word
`latex/typst` с `pandoc` конвертером

### Powerpoint
`slidev`, `reveal.js`, `presenterm`, `slides`

### Video Editors
`remotion`, `revideo`

---
layout: end
---
## Мой вам совет: *ищите новые инструменты*.
## И тогда вы точно прочувствуете *тру vibecoding*

---
layout: end
---

# Спасибо за внимание
