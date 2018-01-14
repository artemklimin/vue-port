<template lang="pug">
    .front-footer
        .footer-top
          Footer-Links
          Footer-Social
        .footer-bottom
          Footer-Text
          Footer-Copyright
</template>

<script>
export default {
  components: {
    FooterLinks: require('../FrontFooter/FooterLinks'),
    FooterSocial: require('../FrontFooter/FooterSocial'),
    FooterText: require('../FrontFooter/FooterText'),
    FooterCopyright: require('../FrontFooter/FooterCopyright')
  }
}
</script>

<style src="./style.scss" lang="scss" scoped></style>
