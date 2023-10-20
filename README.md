# BEM Examples

## Block-level syntax
```
<div class="header">
```


## Multiple word Block
```
<nav class="nav-bar">
```

## Title element inside Header block
```
<h2 class="header__title">
```

## Multiple elements inside a block
```
<nav class="nav-bar">
    <a href="#" class="nav-bar__link">
        <span class="nav-bar__text">
    </span>
  </a>
</nav>
```


## Modified block
```
<a href="#" class="button button--success">
```

## Modified element
```
<a href="#" class="nav-bar__link nav-bar__link--active">
```

# BEM Demo: Planning Stage
- nav.nav
    - ul.nav__list
        - li.nav__item
            - a.nav__link
            - a.nav__link--active

- h1.page-title

- section.plans
    - h2.plans__title

    - ul.plans__options
        - li.plan-type
            - h3.plan-type__tier
            - p.plan-type__description
            - span.plan-type__price
            - button.plan-type__button
        - li.plan-type--recommended

- section.billing
    - h2.billing__title
    - ul.billing__cycles
        - li.billing__period
        - li.billing__period--selected
    - button.billing__pay-now