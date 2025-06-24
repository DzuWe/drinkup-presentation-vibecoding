<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-click="1" />
<div class="image third" v-if="$clicks > 1" />

<div class="content">

# Трекбол

- Для ленивых, минимальное движение кистью
<v-clicks>

- Может быть комбинирован с мышью
- Много opensource решений

</v-clicks>

<v-click>

<br>

### Цена вопроса

Дешевые - 💩 + 🪵 или 🍺🍺🍺🍺🍺

Нормальные - от 🍺x30

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
        background: url('/trackball/trackball-modern.webp');
        background-size: cover;
        background-position: 50%;
    }
    &.second {
        background: url('/trackball/trackball-mouse.jpg');
        background-size: cover;
        background-position: 50%;
    }
    &.third {
        background: url('/trackball/MG_9954-1-scaled.jpg');
        background-size: cover;
        background-position: 50%;
    }
}
</style>
