Hover Effects SaSS
==================

[![Build Status](https://travis-ci.org/idmontie/hover-effects.svg)](https://travis-ci.org/idmontie/hover-effects)

Hover effects based off of the demos available on [Tympanus](http://tympanus.net/Development/HoverEffectIdeas/).

# Usage

In order to use the hover effects, you will need to include the styles using one of the following methods:

* Include `build/hover-effects.min.css` in your project
* If you are using SASS, you can include the project with `@import src/hover-effects.scss`.

# Example Markup

The following is a hover effect example that uses lily.

```html
<div class="hover-effect">
  <figure class="effect-lily">
    <img src="img/coffee.jpg" alt="coffee cup"/>
    <figcaption>
      <div>
        <h2>Nice <span>Lily</span></h2>
        <p>Lily likes to play with crayons and pencils</p>
      </div>
      <a href="#">View more</a>
    </figcaption>
  </figure>
</div>
```

The following effects are available the use the same markup for all of them:

* apollo
* bubba
* chico
* dexter
* duke
* goliath
* hera
* honey
* jazz
* julia
* kira
* layla
* lexi
* lily
* marley
* milo
* ming
* moses
* oscar
* phoebe
* romeo
* roxy
* ruby
* sadie
* sarah
* selena
* steve
* terry
* winston
* zoe

Certain effects will require special markup in the `<p>` tag for the complete "effect" so that it looks like this:

```html
<figcaption>
  <div>
    <h2><span>Zoe</span></h2>
    <p class="icon-links">
      <a href="#">A</a>
      <a href="#">B</a>
      <a href="#">C</a>
    </p>
    <p class="description">Zoe never had the patience of her sisters. She deliberately punched the bear in his face.</p>
  </div>
  <a href="#">View more</a>
</figcaption>
```

# Demo

If you clone the repo, a demo is available: `demo/index.html`