<div class="image first" v-if="$clicks <= 1" />
<div class="image second" v-if="$clicks > 1" />

<div class="content">

# Кронштейны

- Позволяют располагать мониторы друг над другом. Работай лежа если хочешь!
<v-clicks>

- Добавляют свободного места на столе<br> под 🍺
- Существуют кронштейны и под ноуты

</v-clicks>

<v-click>

<br>

### Цена вопроса

от 🍺🍺🍺

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
        background: url('/onkron_G280.png');
        background-size: cover;
    }
    &.second {
        background-image: url('/DSC_0665.webp');
        background-size: cover;
    }
}
</style>
