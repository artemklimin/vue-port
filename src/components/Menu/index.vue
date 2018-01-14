<template lang="pug">
  .menu
    ul.menu-list
      router-link(
        v-for="(menu, index) in menus"
        :key="index"
        tag="li"
        active-class="active"
        :to="menu.route"
        exact
      ).menu-item
        span.menu-link {{menu.name}}
</template>

<script>
export default {
  data: () => ({
    menus: [
      { name: 'Главная', route: '/' },
      { name: 'Обо мне', route: '/F-About' },
      { name: 'Блог', route: '/F-Blog' },
      { name: 'Мои работы', route: '/F-Works' }
    ]
  })
}
</script>

<style src="./style.scss" lang="scss" scoped></style>
