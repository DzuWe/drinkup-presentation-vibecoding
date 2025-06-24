<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-click="1" />
<div class="image third" v-click="2" />
<div class="image forth" v-click="3" />

<div class="content">

# Самодельные штуки

- Мыж инженеры. Время творить
<v-clicks>

- Можно сделать модную метеостанцию
- Или закодить туррель, чтоб отбиваться от коллег
- Даже Pewdiepie (игровой ютубер) замутил себе собственный будильник в виде `BMO`
</v-clicks>

<v-click>

<br>

### Цена вопроса

Arduino - 🍺

Набор электрика - 🍺🍺🍺🍺

Raspberry - 🍺x20

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
        background: url('/custom/8accbf895f7290582be7ab2101ffa117-2535513382.jpg');
        background-size: cover;
        background-position: 30%;
    }
    &.second {
        background: url('/custom/Raspberry-Pi-Based-Weather-Station-768x576-2579557066.jpg');
        background-size: cover;
        background-position: 50%;
    }
    &.third {
        background: url('/custom/nerf-turret.jpg');
        background-size: cover;
        background-position: 30%;
    }

    &.forth {
        background: url('/custom/pewdipie.jpg');
        background-size: cover;
        background-position: 30%;
    }
}
</style>


---

# Кстати
<img class="mx-auto h-90%" src="/custom/photo_2024-12-12_14-51-35.jpg" />
