<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-if="$clicks === 1" />
<div class="image third" v-if="$clicks === 2" />
<div class="image forth" v-if="$clicks === 3" />
<div class="image fifth" v-if="$clicks === 4" />
<div class="content">

# Что еще из железа?

- Беспроводные зарядки, подставки

<v-clicks>

- Удобные стулья
- Грамотное освещение
- Холодильники под ПИИИИВО
- Да что угодно, чтоб тебе было вайбово

</v-clicks>

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
        background: url('/others/stand.jpg');
        background-size: cover;
    }

    &.second {
        background: url('/others/chair.jpg');
        background-size: cover;
    }

    &.third {
        background: url('/others/Monsoon-RGB-5142701_1-837714433.jpg');
        background-size: cover;
        background-position: 30%;
    }

    &.forth {
        background: url('/others/bear.jpg');
        background-size: cover;
        background-position: 30%;
    }

    &.fifth {
        background: url('/others/hardware.jpg');
        background-size: cover;
        background-position: 30%;
    }
}
</style>

---

# Итого по деньгам
Подъемный стол + Стул + 2 кронштейна + Клавиатура + Мышь выходит

<div class="mx-auto w-200">
<span v-for="n of 107" :style="{'--delay': `${n * 10}ms`}" class="appearbear">🍺</span>
<span  :style="{'--delay': `${107*10}ms`}" class="appearbear">&nbsp;~ 107</span>

</div>

<style>
.appearbear {
    font-size: 36px;
    opacity: 0;
    animation: 1s appear linear forwards;
    animation-delay: var(--delay, 0);
}
@keyframes appear {
 to {
    opacity: 1
}
}
</style>
