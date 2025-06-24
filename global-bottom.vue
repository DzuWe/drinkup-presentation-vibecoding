<template>
  <footer v-if="
    !['end'].includes($nav.currentLayout) &&
    ![1].includes($nav.currentPage)
  "
    :class="{
      'mini': ['image', 'fact'].includes($nav.currentLayout)
    }"
  >
    {{ $nav.currentPage }} / {{ $nav.total }}
  </footer>
</template>

<style>
footer {
  position: absolute;
  background: #11111BAA;
  border-radius: 12px;
  padding: 0.1em 0.5em;
  color: #CACACA;
  z-index: 200;
  bottom: 1em;
  right: 1em;
}

footer.mini {
  font-size: 12px;
  bottom: 1em;
  right: 1em;
}
</style>
