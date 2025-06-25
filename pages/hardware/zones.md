---
layout: fact
---
### Немного про эргономику:

## **5** зон рабочего места

<style>
h2 {
    margin-top: 24px;
    font-size: 60px;
}
</style>

---
layout: image
image: /my-deck.jpg
---
<h2 class="floating">Рабочие зоны</h2>


<div v-click class="zone bottom-0 left-40 w-70 h-55">
        <span>Основная</span>
</div>

<div v-click class="zone green bottom-60 left-0 w-50 h-30">
        <span>Вторичная</span>
</div>

<div v-click class="zone red bottom-0 left-0 w-40 h-20">
        <span>Хранение</span>
</div>

<div v-click class="zone yellow top-20 right-0 w-70 h-100">
        <span>Референсная</span>
</div>

<div v-click class="zone cyan top-65 left-50 w-120 h-20">
        <span>Личная</span>
</div>



<style>
.zone {
    --clr: var(--purple);
    display: grid;
    place-items: center;
    position: absolute;
    padding: 12px;
    color: var(--clr);
    font-weight: bold;
    background: #141414AA;
    border: 1px solid var(--clr);
    border-radius: 12px;
    span {
        background: #141414AA;
        font-size: 25px;
        padding: 2px 8px;
        border-radius: 6px;
        backdrop-filter: blur(12px);
    }
    &.green {
        --clr: var(--green);
    }

    &.yellow {
        --clr: var(--yellow);
    }

    &.red {
        --clr: var(--red);
    }

    &.cyan {
        rotate: 20deg;
        --clr: var(--cyan);
    }
    
}

</style>
