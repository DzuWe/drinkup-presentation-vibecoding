<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-if="$clicks > 0" />

<div class="content">

# Тачпад

- Привычен, большинство ноутов с ним
<v-clicks>

- Поддержка различных жестов
- Можно использовать отдельно

</v-clicks>

<v-click>

<br>

### Цена вопроса

Дешевые - 🍺🍺🍺

Нормальные - от 🍺x20

</v-click>

</div>

<style>
.content {
    padding-left: calc(50% + 2em);
}
.image {
    width: 50%;
    position: absolute;
    height: 100%;
    top: 0;
    left: 0;
    &.first {
        background: url('/touchpad/pc-touchpad.jpg');
        background-size: cover;
        background-position: 30%;
    }
    &.second {
        background-color: white;
        background-image: url('/touchpad/cheap.jpg');
        background-size: 110%;
        background-repeat: no-repeat;
        background-position: center center;
    }
}
</style>
