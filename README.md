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
.header>.header__wrapper>(.header__logo .logo>.logo__image)+(.header__navigation .navigation>.navigation__list>.navigation__item*4>.navigation__link)+.header__button+.header__button--basket
```

### form 
![form](/img/form.png "form")
```
.footer__feedback .feedback>.feedback__wrapper>.feedback__heading+.feedback__subheading+(.feedback__form .form>(.feedback__label*4>.feedback__input)+(.feedback__label>.textarea))+.feedback__button
```

### card-block 
![card-block](/img/card-block.png "card-block")
```
.main__product .product>.product__wrapper>.product__list>.product__item*6>(.product__image+.product__heading+.product__text)
```

### info
![info](/img/info.png "info")
```
section.main__history.history>div.history__part>(div.history__content>h3.history__heading+p.history__paragraph*2)+div.history__image-wrapper>img.history__image
```
```
section.main__history.history>div.history__part .history__part--reverse>(div.history__content>h3.history__heading+p.history__paragraph*3+a.history__link)+div.history__image-wrapper>img.history__image
```
```
section.main__history.history>div.history__part>(div.history__content>h3.history__heading+p.history__paragraph*3)+div.history__image-wrapper>img.history__image
```


