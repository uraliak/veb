# BEM
## Task 1
`.people-body`
`.people-body__head .head`
`.people-body__arm .arm`
`.people-body__leg .leg`
`.head`
`.head--hair_dark`
`.arm`
`.arm--ring_gold`
`.leg`
`.leg--decoration_yellow`

## Task 2
### header
![header](/img/header.png "header")
```
.header>.header__wrapper>(.header__logo .logo>.logo__image)+(.header__navigation .navigation>.navigation__list>.navigation__item*4)+(.header__button>.header__button--basket)
```

### form 
![form](/img/form.png "form")
```
.footer__feedback .feedback>.feedback__wrapper>.feedback__heading+.feedback__subheading+(.feedback__form .form>.form__wrapper>.feedback__label*5>.feedback__input)+(.feedback__button>.feedback__button--text)
```

### card-block 
![card-block](/img/card-block.png "card-block")
```
.main__product .product>.product__wrapper>.product__list>.product__item*6>(.product__image+.product__heading+.product__text)
```

### info
![info](/img/info.png "info")
```
.main__history .history>.history__wrapper>(.history__sidebar .sidebar*2>.sidebar__heading+.sidebar__text*2+.sidebar__image)+(.history__sidebar--reverse .sidebar--reverse>.sidebar--reverse__image+.sidebar--reverse__heding+.sidebar--reverse__text*2+(.sidebar--reverse__button .button>.button__text))
```
