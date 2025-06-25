<h1 class="floating top-10">Тайловые менеджеры окон (Tilling WM)</h1>

<video autoplay class="mx-a" src="/outfoxxed.mp4" loop/>
<p class="absolute bottom-2 font-size-3 text-gray-500 text-center">(hyprland)</p>

<div v-if="$clicks === 0" class="floating  feature top-30">
Главная фича: <br>
<strong>Эффективное управление рабочим пространством</strong>
</div>

<div v-click class="floating glassy top-30 grid" > 
<h3>Особи:</h3>

<div>
<strong>Линух</strong>

- hyprland
- i3
- XMonad
</div>

<div>
<strong>Макось</strong>

- Aerospace 🍺 
- Ametist 
- Yabai
</div>

<div>
<strong>Винда</strong>

- komorebi
- GlazeWM
</div>


</div>

<style>
.grid {
    padding: 12px;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px 2em;
    h3 {
        grid-column: 1 / span 3;
    }
     
}
.feature {
    font-size: 25px !important;
}

video {
    position: absolute;
    inset: 0;
    z-index: 0;
}
</style>
