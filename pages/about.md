<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-if="$clicks === 1" />
<div class="image third" v-if="$clicks === 2" />
<div class="image grid place-items-center" v-if="$clicks === 3"> 
    <div class="text-center font-size-10">
        <strong>ШУТКА</strong><br> сегодня без духоты 
    </div>
</div>
<div class="image forth" v-if="$clicks === 4" />

<div class="content">

# А говорить буду про:

- Недооцененные штуки
<v-clicks>

- Гиковые гаджеты
- Разные программы

</v-clicks>

<v-click at="4">

- Ricing
- и другие полезные штуки, как сделать кодинг вайбовым

</v-click>

</div>

<style>
.content {
    padding-right: calc(50% + 2em);
}
.image {
    width: 50%;
    position: absolute;
    height: 100%;
    top: 0;
    right: 0;
    &.first {
        background: url('/keyboard.jpg');
        background-size: cover;
    }
    &.second {
        background-image: url('/geek.jpg');
        background-size: cover;
    }
    &.third {
        background-image: url('/vim.jpg');
        background-size: cover;
        background-position: 50%;
    }

    &.forth {
        background-image: url('/ricing.png');
        background-size: cover;
        background-position: 50%;
    }
}
</style>
