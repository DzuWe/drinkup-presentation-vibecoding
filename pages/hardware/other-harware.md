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
