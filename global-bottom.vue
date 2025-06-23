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
  color: #585b70;
  z-index: 200;
  bottom: 1em;
  right: 1em;
}

footer.mini {
  font-size: 12px;
  color: #45475a;
  bottom: 1em;
  right: 1em;
}
</style>
