<template lang="pug">
    .front1
        .auth-button
            Auth-Link
        .center-container
            .center-block
                I-Top
                CB-Social
                CB-Buttons
        .footer © Артем Климин | создано с любовью в LoftSchool | 2017-2018 
</template>

<script>
export default {
  components: {
    AuthLink: require('../AuthLink'),
    ITop: require('../ITop'),
    CBSocial: require('../CBSocial'),
    CBButtons: require('../CBButtons')
  }
}
</script>


<style src="./style.scss" lang="scss" scoped></style>