<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-click="1" />
<div class="image third" v-click="2" />
<div class="image first" v-click="3" />

<div class="content">

# Мышь

- Они везде
<v-clicks>

- Бывают вертикальные
- Бывают максимально странных форм и решений
</v-clicks>

<v-click>

<br>

### Цена вопроса

Дешевые - 🍺

Нормальные - от 🍺🍺🍺🍺🍺

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
        background: url('/mouse/AltoMouse.jpg');
        background-size: cover;
        background-position: 30%;
    }
    &.third {
        background: url('/mouse/DogPCMouse_1.jpg');
        background-size: cover;
        background-position: 30%;
    }
    &.second {
        background: url('/mouse/vertical.jpg');
        background-size: cover;
        background-position: 50%;
    }
}
</style>
