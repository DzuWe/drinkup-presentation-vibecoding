---
layout: fact
class: text-align-start
---

1) Берем пиво
2) Натягиваем худи 
3) Запускаем IDE
4) и идем решать стандартные задачи при помощи программирования 

<style>
ol {
    font-size: 40px;
    text-align: left;
}
</style>

---

<h1 class="floating">Верстаем презентации</h1>
<v-click>
<div class="floating top-30">
<h3>Альтернативы</h3>

- reveal.js
- presenterm
- slides
</div>
</v-click>

<video autoplay loop src="/coding/slidev.mov" />

<style>
video {
    position: absolute;
    inset: 0;
}
</style>

---

<h1 class="floating">Замена WORD</h1>

<v-click>
    <h3 class="floating top-30">LateX/Typst + <strong>pandoc</strong> = docx</h3>
</v-click>

<video autoplay loop src="/coding/typst.webm" />

<style>
video {
    position: absolute;
    top: 25%;
    left: 0;
}
</style>

---

<h1 class="floating">Клепаем видео</h1>

<v-click>
<div class="floating top-30 w-100">
<h3> Особи </h3>

- <span class="text-orange">💩remotion💩</span> (тут реактом попахивает)
- `re.video` (тут вроде как можно подрубить  Vue, с плясками)
- `ffmpeg` (Женя Кучерявый говорил что может и на нем фигачить видосы)
</div>
</v-click>

<video :class="{shift: $clicks === 1}" autoplay loop src="/coding/Remotion.webm" />

<style>
video {
    position: absolute;
    width: 400px;
    top: 50%;
    left: 50%;
    translate: -50% -50%;
    transition: 0.5s ease-in-out left;
    &.shift {
        left: 75%
    }
}
</style>

---

<h1 class="floating">Пишем музыку (strudel.cc)</h1>

<video autoplay loop src="/coding/strudel.mov" />

<img src="/coding/strudel_icon.png" />

<style>
img {
    position: absolute;
    width: 150px;
    top: 50%;
    transform: translateY(-50%);
    left: 11em;
}
video {
    position: absolute;
    width: 400px;
    top: 50%;
    transform: translateY(-50%);
    right: 1em;
}
</style>
