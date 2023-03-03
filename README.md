# BEM
## Task 1
`.human`
`.human__head .head`
`.human__arm .arm`
`.human__leg .leg`
`.head`
`.head--hair-dark`
`.arm`
`.arm--ring-gold`
`.leg`
`.leg--decoration-yellow`

## Task 2
### header
![header](/img/header.png "header")
```
class.header>div.header__wrapper>(a.header__logo.logo>img.logo__image)+(nav.header__navigation.navigation>ul.navigation__list>li.navigation__item*4>a.navigation__link)+button.header__button--basket
```

### form 
![form](/img/form.png "form")
```
class.footer__feedback.feedback>div.feedback__wrapper>h2.feedback__heading+h3.feedback__subheading+(form.feedback__form.form>(label.feedback__label*4>input.feedback__input)+(label.feedback__label>textarea.feedback__textarea))+button.feedback__button
```

### card-block 
![card-block](/img/card-block.png "card-block")
```
class.main__products.products>div.products__wrapper>ul.products__list>li.products__item*6>(img.products__image+h2.products__heading+p.products__text)
```

### info
![info](/img/info.png "info")
```
section.main__history.history>
div.history__card.card>(div.card__content>h3.card__heading+p.card__paragraph*2)+div.card__image-wrapper>img.card__image
div.history__card.card.card__part--reverse>(div.card__content>h3.card__heading+p.card__paragraph*3+a.card__link)+div.card__image-wrapper>img.card__image
div.history__card.card>(div.card__content>h3.card__heading+p.card__paragraph*3)+div.card__image-wrapper>img.card__image
```
