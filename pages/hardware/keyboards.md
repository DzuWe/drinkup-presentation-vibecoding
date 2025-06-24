<div class="image first" v-if="$clicks < 1" />
<div class="image second" v-click="1" />
<div class="image third" v-click="2" />
<div class="image forth" v-click="3" />
<div class="image fifth" v-if="$clicks > 3" />

<div class="content">

# Клавиатуры

- Сердце разработки
<v-clicks>

- Могут быть разных форм
- Разных размеров
- Из разных материалов
- Много opensource решений

</v-clicks>

<v-click>

<br>

### Цена вопроса

Дешевые - 💩 + 🪵 или 🍺

Нормальные - от 🍺x15 и до бесконечности

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
        background: url('/keyboards/IBM_model_m_rotate.jpg');
        background-size: cover;
        background-position: 50%;
    }
    &.second {
        background: white;
        background-image: url('/keyboards/rounded.jpg');
        background-repeat: no-repeat;
        background-size: 120%;
        background-position: center center;
    }
    &.third {
        background: url('/keyboards/the-key-stack-overflow-copy-paste-keyboard.jpg');
        background-size: cover;
        background-position: 50%;
    }

    &.forth {
        background: url('/keyboards/Oree-Wooden-Keyboard-4-2819302094.jpg');
        background-size: cover;
        background-position: 50%;
    }
    
    &.fifth {
        background: url('/keyboards/ic-open-source-keyboards-by-cablesutra-v0-edu77in16flb1-3449345440.jpg');
        background-size: cover;
        background-position: 50%;
    }
}
</style>

---

<div class="image first" v-if="$clicks < 1">
    <img width="200" src="/keyboards/nonsplit.jpg" />
</div>
<div class="image second" v-click="1" />

<div class="content">

# Немного про кастом клавиатуры

- Бывают как split версии так и цельные
<v-click>

- сверх кастомизируемая:

`подсветка`, `раскладка`, `свитчи`, `материалы`, `прошивка`, `кейкапы и тд`
    
</v-click>


<v-click>

- Не обязательно уметь паять. На маркетплейсах есть умельцы которые спаяют за тебя
</v-click>
<br>
<v-click>

### Цена вопроса

💩 + 🪵 или от 🍺x15 в среднем

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
        background: url('/keyboards/home-01.avif');
        background-size: 50%;
        background-position: 70% 70%;
        background-repeat: no-repeat;
        rotate: 45deg;
        scale: 1.2;
        img {
            position: absolute;
            rotate: -90deg;
            top: 25%;
            left: 20%;
            scale: 1.2;
            border-radius: 12px;
        }
        
    }
    &.second {
        background-image: url('/keyboards/my-second-custom-build-split-ergo-5x3-with-encoders-and-v0-6l0pv9vjurma1-462493897.jpg');
        background-position: center;
        background-size: cover;
    }
    &.third {
        background: url('/keyboards/the-key-stack-overflow-copy-paste-keyboard.jpg');
        background-size: cover;
        background-position: 50%;
    }

    &.forth {
        background: url('/keyboards/Oree-Wooden-Keyboard-4-2819302094.jpg');
        background-size: cover;
        background-position: 50%;
    }
    
    &.fifth {
        background: url('/keyboards/ic-open-source-keyboards-by-cablesutra-v0-edu77in16flb1-3449345440.jpg');
        background-size: cover;
        background-position: 50%;
    }
}
</style>

---

<div class="image first" v-if="$clicks < 1">
    <img src="/keyboards/qmk-logo-light.svg" />
    <img src="/keyboards/zmk.png" />
    <img src="/keyboards/icon-4231055634.png" />
</div>

<div class="image solo" v-if="$clicks === 1"> 
    <img src="/keyboards/qmk-logo-light.svg" />
</div>

<div class="image solo" v-if="$clicks === 2"> 
    <img src="/keyboards/zmk.png" />
</div>

<div class="image solo" v-if="$clicks === 3"> 
    <img src="/keyboards/icon-4231055634.png" />
</div>



<div class="content">

# Немного про прошивки

- Основные QMK/ZMK/VIA
<v-click>

- **QMK**
    - Огромная поддержка устройств
    - Старожил прошивок
</v-click>

<v-click>

- **ZMK**
    - Wireless first
    - что-то типа форка QMK
</v-click>

<v-click>

- **VIA**
    - Легкая кофигурация через вебморду
    - Более современная
</v-click>

</div>

<style>
.content {
    padding-left: calc(50% + 2em);
}
.shortcut {
    padding: 12px;
    display: flex;
    align-items: center;
    gap: 8px;
    height: 50px;

    img { height: 50px;}
}
.image {
    width: 50%;
    position: absolute;
    height: 100%;
    top: 0;
    left: 0;


    &.first {
        img {
            margin: 24px auto;
            max-width: 150px;
            rotate: -10deg;
            &:first-child,
            &:last-child {
                rotate: 10deg;
            }
        }
    }
    &.solo img {
        width: 300px;
        position: absolute;
        top: 50%;
        left: 50%;
        translate: -50% -50%;
    }
}
</style>

---
layout: two-cols
---

# Фишки кастомных прошивок

<v-clicks>

<div>
Модификаторы поведения например:

- **Mod-tap**

<div class="shortcut">
    <img src="/keyboards/shortcuts/key-tap-a.png"/> =>
    <img src="/keyboards/shortcuts/key-a.png"/>
</div>
<div class="shortcut">
    <img src="/keyboards/shortcuts/key-hold-a.png"/> =>
    <img src="/keyboards/shortcuts/command.png"/>
</div>
</div>

<div class="mt-4">

- **Tapdance**

<div class="shortcut">
    <img src="/keyboards/shortcuts/key-b.png"/> =>
    <img src="/keyboards/shortcuts/key-b.png"/>
</div>
<div class="shortcut">
    <img src="/keyboards/shortcuts/key-b.png"/>
    <img src="/keyboards/shortcuts/key-b.png"/> =>
    <img src="/keyboards/shortcuts/bear.png"/>
</div>
</div>

</v-clicks>

::right::
<div class="mt-20">
<v-click>

- **Настраиваемые раскладки**
- **Макросы**
- **Слои** 


</v-click>
<v-click>
<br>

> и многое другое

</v-click>

</div>

<style>
.shortcut {
    padding: 12px;
    display: flex;
    align-items: center;
    gap: 8px;
    height: 50px;

    img { height: 50px;}
}
blockquote {
    font-size: 20px;
}
</style>
