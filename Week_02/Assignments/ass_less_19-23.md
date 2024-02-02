# Week_02

## Lessons_From_19_to_23

### assignment_01

- search for HTML Elements

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>week_02_assign_01</title>
  </head>
  <body>
    <!--
        HTML Element:
        1- <header></header>
        2- <nav></nav>
        3- <main></main>
        4- <aside></aside>
        5- <Picture></Picture>
        6- <figure></figure>
        7- <footer></footer>
        8- <figcaption></figcaption>
        9- <section></section>
        10- <ruby></ruby>
        11- <article></article>
        12- <data></data>
    -->
  </body>
</html>
```

- Try to know the differences between <section> and <article> tags

### assignment_02

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Assignment_02_Test_Semantic_Elements</title>
    <meta
      name="description"
      content="new products in 2023 keyboards, mouses, speakers, etc..."
    />
  </head>
  <body>
    <header>
      <h1>Hardware Market</h1>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Profile</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contanct Us</a></li>
        <li><a href="#">Deals</a></li>
      </ul>
    </header>
    <nav>
      <ul>
        <li><a href="#keyboards">Keyboards</a></li>
        <li><a href="#mouses">Mouses</a></li>
        <li><a href="#speakers">Speakers</a></li>
        <li><a href="#">Mouse Pads</a></li>
        <li><a href="#">GamePad</a></li>
        <li><a href="#">Headsets</a></li>
        <li><a href="#">Streaming</a></li>
      </ul>
    </nav>
    <main>
      <article>
        <section id="Keyboards">
          <h2>Keyboards</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus
            consequuntur nihil, cumque omnis odit minima reiciendis dolor nisi
            asperiores eveniet quaerat illum fuga tempora ut corporis! Eveniet,
            consequuntur assumenda? Deserunt?
          </p>
          <figure>
            <img src="images/Html.jpg" alt="" />
            <figcaption><a href="#">read more</a></figcaption>
          </figure>
        </section>
        <hr />
        <section id="mouses">
          <h2>Mouses</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus
            consequuntur nihil, cumque omnis odit minima reiciendis dolor nisi
            asperiores eveniet quaerat illum fuga tempora ut corporis! Eveniet,
            consequuntur assumenda? Deserunt?
          </p>
          <figure>
            <img src="images/Html.jpg" alt="" />
            <figcaption><a href="#">read more</a></figcaption>
          </figure>
        </section>
        <hr />
        <section id="speakers">
          <h2>Speakers</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus
            consequuntur nihil, cumque omnis odit minima reiciendis dolor nisi
            asperiores eveniet quaerat illum fuga tempora ut corporis! Eveniet,
            consequuntur assumenda? Deserunt?
          </p>
          <figure>
            <img src="images/Html.jpg" alt="" />
            <figcaption><a href="#">read more</a></figcaption>
          </figure>
        </section>
      </article>
    </main>
    <aside>
      <h3>Categories</h3>
      <ul>
        <li>keyboard</li>
        <li>speaker</li>
        <li>mouse</li>
        <li>headset</li>
        <li>streaming</li>
      </ul>
    </aside>
    <footer>
      <p>
        Copyright 2023 <small><sup>&copy;</sup></small>
      </p>
    </footer>
  </body>
</html>
```

### assignment_03

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>assignment_03_week_02</title>
  </head>
  <h1>Audio Example</h1>
  <body>
    <audio controls autoplay loop muted>
      <source src="media/071.mp3" type="audio/mpeg" />
      <source src="media/audio/071.ogg" type="audio/ogg" />
      <source src="media/audio/071.wav" type="audio/wav" />
      Your browser doesn't support audio
    </audio>
  </body>
</html>
```

### assignment_04

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>assignment_04_week_02</title>
  </head>
  <body>
    <h1>Video Example</h1>
    <video controls muted loop autoplay width="400" height="400" poster="images/Html.jpg">
      <source src="media/video/Zakir_The_Messengers_of_God.mp4" type="video/mp4" />
      <source src="media/video/Zakir_The_Messengers_of_God.ogg" type="video/ogg"/>
      <source src="media/video/Zakir_The_Messengers_of_God.mpeg" type="video/mpeg" />
      <track src="en.vtt" kind="subtitles" srclang="en" label="English" />
      <track src="it.vtt" kind="subtitles" srclang="it" label="Italian" />
      Your browser does not support the video tag.
    </video>
  </body>
</html>
```
