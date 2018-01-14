<template lang="pug">
  .app-full
    .content
      router-view

    .front2
      .social
        Front-Top-Social
      .menu
        Front-Top-Menu
      .front-header
        .header-top-block
          I-Top
        .header-bottom-block
          To-Bottom-Arrow
      .front-middle

</template>

<script>
export default {
  components: {
    Tabs: require('Tabs'),
    Menu: require('Menu'),
    AppHeader: require('Header'),
    FrontTopSocial: require('FrontTopSocial'),
    FrontTopMenu: require('FrontTopMenu'),
    ToBottomArrow: require('ToBottomArrow')
  }
}
</script>