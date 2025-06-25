<h1 class="floating border b-purple">Виртуальные указатели</h1>

<img src="/clideo_editor_544db91860674585bcbc219c2e92bb5f.gif"/>

<div  v-click="[1]" class="floating bottom-20">

- Удобное управление мышью с клавиатуры
- Прекрасно сочетаются с Tilling WM
- Клавиатура быстрее мыши
</div>

<div  v-click="2" class="floating  bottom-20  grid">
<h3>Особи: </h3>
<div>
<strong>Линух</strong>

- warpd 🍺
- rat
</div>
<div>
<strong>Макось</strong>

- warpd 🍺
- keytty
- mousio
</div>
<div>
<strong>Винда</strong>

- не нашел
</div>
</div>

<style>

.grid {
    padding: 12px;
    grid-template-columns: repeat(3, 1fr);
    gap: 8px 1em;
    h3 {
        grid-column: 1 / span 3;
    }
     
}
img {
    width: 100vh;
    position: absolute;
    inset: 0;
}
</style>
