---
id: 587d78ab367417b2b2512af1
title: Add Flex Superpowers to the Tweet Embed
challengeType: 0
videoUrl: ''
localeTitle: Añadir los superpoderes de Flex al visualizador de Tweet
---

## Description
<section id="description"> A la derecha se encuentra un listado de tweets insertados que se utilizará como ejemplo práctico. Algunos de los elementos se verían mejor con un diseño diferente. En el último desafío se utilizó la propiedad <code>display: flex</code> . Aquí lo añadirá a algunas partes en el listado de tweets para comenzar a ajustar su posicionamiento. </section>

## Instructions
<section id="instructions"> Agregue la propiedad css <code>display: flex</code> a los siguientes elementos. Tenga en cuenta que los selectores css ya están configurados: <code>header</code>, <code>.profile-name</code> y <code>.follow-btn</code> del encabezado, <code>.follow-btn</code> del encabezado, el <code>h3</code> y el <code>h4</code> del encabezado, el <code>footer</code> , y los <code>.stats</code> en la parte inferior de <code>.stats</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Su <code>header</code> debe tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($("header").css("display") == "flex", "Your <code>header</code> should have a <code>display</code> property set to flex.");'
  - text: Su <code>footer</code> debe tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($("footer").css("display") == "flex", "Your <code>footer</code> should have a <code>display</code> property set to flex.");'
  - text: Tu <code>h3</code> debería tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($("h3").css("display") == "flex", "Your <code>h3</code> should have a <code>display</code> property set to flex.");'
  - text: Tu <code>h4</code> debería tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($("h4").css("display") == "flex", "Your <code>h4</code> should have a <code>display</code> property set to flex.");'
  - text: Su <code>.profile-name</code> debe tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($(".profile-name").css("display") == "flex", "Your <code>.profile-name</code> should have a <code>display</code> property set to flex.");'
  - text: Su <code>.follow-btn</code> debe tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($(".follow-btn").css("display") == "flex", "Your <code>.follow-btn</code> should have a <code>display</code> property set to flex.");'
  - text: Sus <code>.stats</code> deben tener una propiedad de <code>display</code> configurada para flexionar.
    testString: 'assert($(".stats").css("display") == "flex", "Your <code>.stats</code> should have a <code>display</code> property set to flex.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header {

  }
  header .profile-thumbnail {
    width: 50px;
    height: 50px;
    border-radius: 4px;
  }
  header .profile-name {

    margin-left: 10px;
  }
  header .follow-btn {

    margin: 0 0 0 auto;
  }
  header .follow-btn button {
    border: 0;
    border-radius: 3px;
    padding: 5px;
  }
  header h3, header h4 {

    margin: 0;
  }
  #inner p {
    margin-bottom: 10px;
    font-size: 20px;
  }
  #inner hr {
    margin: 20px 0;
    border-style: solid;
    opacity: 0.1;
  }
  footer {

  }
  footer .stats {

    font-size: 15px;
  }
  footer .stats strong {
    font-size: 18px;
  }
  footer .stats .likes {
    margin-left: 10px;
  }
  footer .cta {
    margin-left: auto;
  }
  footer .cta button {
    border: 0;
    background: transparent;
  }
</style>
<header>
  <img src="https://pbs.twimg.com/profile_images/378800000147359764/54dc9a5c34e912f34db8662d53d16a39_400x400.png" alt="Quincy Larson's profile picture" class="profile-thumbnail">
  <div class="profile-name">
    <h3>Quincy Larson</h3>
    <h4>@ossia</h4>
  </div>
  <div class="follow-btn">
    <button>Follow</button>
  </div>
</header>
<div id="inner">
  <p>I meet so many people who are in search of that one trick that will help them work smart. Even if you work smart, you still have to work hard.</p>
  <span class="date">1:32 PM - 12 Jan 2018</span>
  <hr>
</div>
<footer>
  <div class="stats">
    <div class="Retweets">
      <strong>107</strong> Retweets
    </div>
    <div class="likes">
      <strong>431</strong> Likes
    </div>
  </div>
  <div class="cta">
    <button class="share-btn">Share</button>
    <button class="retweet-btn">Retweet</button>
    <button class="like-btn">Like</button>
  </div>
</footer>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
