# Лабораторная работа №1

## Emmet + BEM (8 вариант)

- ### Шапка (header)

  Скриншот:

  ![Шапка сайта](/images/header.png)

  Emmet:

  ```css
  header.header>.header__wrapper>((a.header__logo>img.header__logo__img)+(nav.header__nav>a.header__link*3))+button.header__button-sandwich
  ```

  HTML:

  ```html
  <header class="header">
    <div class="header__wrapper">
      <a href="" class="header__logo">
        <img src="" alt="" class="header__logo__img" />
      </a>
      <nav class="header__nav">
        <a href="" class="header__link"></a>
        <a href="" class="header__link"></a>
        <a href="" class="header__link"></a>
      </nav>
      <button class="header__button-sandwich"></button>
    </div>
  </header>
  ```

- ### Форма (form)

  Скриншот:

  ![Форма подписки на новостную рассылку](/images/form.png)

  Emmet:

  ```css
  .contact-form>h2.contact-form__title+p.contact-form__paragraph+form.contact-form__form>input[type="email"].contact-form__input+button[type="submit"].contact-form__button
  ```

  HTML:

  ```html
  <div class="contact-form">
    <h2 class="contact-form__title"></h2>
    <p class="contact-form__paragraph"></p>
    <form action="" class="contact-form__form">
      <input type="email" class="contact-form__input" />
      <button type="submit" class="contact-form__button"></button>
    </form>
  </div>
  ```

- ### Карточка (card)

  Скриншот:

  ![Карточка со ссылкой](/images/card.png)

  Emmet:

  ```css
  .card>img.card__image+h3.card__title+a.card__link
  ```

  HTML:

  ```html
  <div class="card">
    <img src="" alt="" class="card__image" />
    <h3 class="card__title"></h3>
    <a href="" class="card__link"></a>
  </div>
  ```

- ### Карточка (card)

  Скриншот:

  ![Карточка со ссылкой](/images/card.png)

  Emmet:

  ```css
  .card>img.card__image+h3.card__title+a.card__link
  ```

  HTML:

  ```html
  <div class="card">
    <img src="" alt="" class="card__image" />
    <h3 class="card__title"></h3>
    <a href="" class="card__link"></a>
  </div>
  ```

- ### Цитата (quote - на выбор)

  Скриншот:

  ![Цитата](/images/quote.png)

  Emmet:

  ```css
  figure.quote>(blockquote.quote__text-wrapper>p.quote__text)+(figcaption.quote__caption>p.quote__author-name+p.quote__author-location)+.quote__button-wrapper>button.quote__button.quote__button--back+button.quote__button.quote__button--forward
  ```

  HTML:

  ```html
  <figure class="quote">
    <blockquote class="quote__text-wrapper">
      <p class="quote__text"></p>
    </blockquote>
    <figcaption class="quote__caption">
      <p class="quote__author-name"></p>
      <p class="quote__author-location"></p>
    </figcaption>
    <div class="quote__button-wrapper">
      <button class="quote__button quote__button--back"></button>
      <button class="quote__button quote__button--forward"></button>
    </div>
  </figure>
  ```
