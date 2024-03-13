content\_\_xxx와 content-xxx의 차이점은?

```
container | is--active
    <!-- S-LOGIC -->
    content | content__main | content-main | is--dark
    <!-- GPT -->
    content | content__gpt | is--dark
    <!-- FIT -->
    content | content__fit | is--light
    <!-- HRA -->
    content | content__hra | is--light
    <!-- reference -->
    content | content__reference | content-reference | is--dark 🧨
        inner ✨
            content_heading
            content_title
            content-reference__button
            content__exposition | content-reference__exposition
        content__guide-message ✨
    <!-- combination -->
    content | content__combination | is--dark
        inner__combination 🎄
            content__heading
            content__description
            content__cards-wrapper
                card 🎫
                    caption
            content__inquiry-wrapper
                info 🎫
    <!-- step -->
    content | content__step | is--light
```

---

```scss
.content
    .inner
        &__combination 🎄
    .fulled-inner
    &__heading ✨🎄
    &__title ✨
    &__sub-title
    &__description 🎄
    &__info
    &__exposition ✨
    &__link
    &__stepper
    &__guide-message ✨
    &__cards-wrapper 🎄
        .card 🎫
            &__caption 🎫
    &__inquiry-wrapper
        .info 🎫

    &.content__main
    &.content__work
    &.content__gpt
    &.content__fit
    &.content__hra
    &.content__step
    &.content__form
    &.content__reference 🧨
        &__button
    &__mouse
    &__footer

.controller
.company-main-page-re .content > .inner.contact-us-form
.contact-us-form
.content-main
.content-reference 🧨
    &__button ✨
.company-main-page-re .content-reference__exposition ✨
```
