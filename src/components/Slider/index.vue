<template lang="pug">
.slider
    .grid-element.left2x2
        ul#slides-description.slides
            li.slide-description.showing
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 1
            li.slide-description
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 2
            li.slide-description
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 3
            li.slide-description
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 1a
            li.slide-description
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 2a
            li.slide-description
                .about-container 
                    .about-left
                        .about-left__info
                            .about-left__my-photo-container
                                img.about-left__img(src="", alt="")
                            .about-left__who-i-am 
                                span.about-left__who-i-am-lines Сайт школы онлайн<br>образовани
                            .about-left__teaser HTML , CSS, JAVASCRIPT
                            a.about-left__button(href="#")
                                svg.link-icon
                                    use(xlink:href="assets/images/sprites.svg#link-icon")
                                span.about-left__button-text Посмотреть сайт 3a
    .grid-element.right2x1
        ul.main-slider#slides.slides
            li.main-slider__item.slide.showing
                img.main-slider__item-image(src="assets/images/work01.png")
            li.main-slider__item.slide
                img.main-slider__item-image(src="assets/images/work01.png")
            li.main-slider__item.slide
                img.main-slider__item-image(src="assets/images/work01.png")
            li.main-slider__item.slide
                img.main-slider__item-image(src="assets/images/work01.png")
            li.main-slider__item.slide
                img.main-slider__item-image(src="assets/images/work01.png")
            li.main-slider__item.slide
                img.main-slider__item-image(src="assets/images/work01.png")
    .grid-element.right1x1
        ul.left-slider#slides2.slides
            li.left-slider__item.slide2
                img.left-slider__item-image(src="assets/images/work01.png")
            li.left-slider__item.slide2.showing
                img.left-slider__item-image(src="assets/images/work01.png")
            li.left-slider__item.slide2
                img.left-slider__item-image(src="assets/images/work01.png")
            li.left-slider__item.slide2
                img.left-slider__item-image(src="assets/images/work01.png")
            li.left-slider__item.slide2
                img.left-slider__item-image(src="assets/images/work01.png")
            li.left-slider__item.slide2
                img.left-slider__item-image(src="assets/images/work01.png")
        .controls.controls-left#previous 
                svg.arrows
                    use(xlink:href="assets/images/sprites.svg#ar-down")
    .grid-element.right1x1-2
        ul.right-slider#slides3.slides
            li.right-slider__item.slide3
                img.right-slider__item-image(src="assets/images/work01.png")
            li.right-slider__item.slide3
                img.right-slider__item-image(src="assets/images/work01.png")
            li.right-slider__item.slide3.showing
                img.right-slider__item-image(src="assets/images/work01.png")
            li.right-slider__item.slide3
                img.right-slider__item-image(src="assets/images/work01.png")
            li.right-slider__item.slide3
                img.right-slider__item-image(src="assets/images/work01.png")
            li.right-slider__item.slide3
                img.right-slider__item-image(src="assets/images/work01.png")
        .controls.controls-right#next 
                svg.arrows
                    use(xlink:href="assets/images/sprites.svg#ar-up")
</template>
