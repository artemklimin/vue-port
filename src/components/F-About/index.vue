<template lang="pug">

    .about
        h1.title Обо мне
        .container
            .my-foto
                img(src="~img/my-foto.jpg")
            h2.title Кто я
            .content
                p Тут идет какой-то описательный текст про меня.
                p Тут он продолжается и окрашивается новыми возможностями.
        h2.title Чем я могу быть Вам полезен
        .intro-text Тут написано что я кмею делать много всего полезного, что напрямую свидлетельствует о том, что я могу быть полезен потенциальному работадателю.
        .skills
            Skill-List
        .footer
            Front-Footer
    
</template>

<script>
export default {
  components: {
    SkillList: require('../SkillList'),
    FrontFooter: require('FrontFooter')
  }
}
</script>

<style src="./style.scss" lang="scss"></style>