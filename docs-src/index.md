---
layout: page.11ty.cjs
title: <flink-mink> ⌲ Home
---

# &lt;flink-mink>

`<flink-mink>` is an awesome element. It's a great introduction to building web components with LitElement, with nice documentation site as well.

## As easy as HTML

<section class="columns">
  <div>

`<flink-mink>` is just an HTML element. You can it anywhere you can use HTML!

```html
<flink-mink></flink-mink>
```

  </div>
  <div>

<flink-mink></flink-mink>

  </div>
</section>

## Configure with attributes

<section class="columns">
  <div>

`<flink-mink>` can be configured with attributed in plain HTML.

```html
<flink-mink name="HTML"></flink-mink>
```

  </div>
  <div>

<flink-mink name="HTML"></flink-mink>

  </div>
</section>

## Declarative rendering

<section class="columns">
  <div>

`<flink-mink>` can be used with declarative rendering libraries like Angular, React, Vue, and lit-html

```js
import {html, render} from 'lit-html';

const name = 'lit-html';

render(
  html`
    <h2>This is a &lt;flink-mink&gt;</h2>
    <flink-mink .name=${name}></flink-mink>
  `,
  document.body
);
```

  </div>
  <div>

<h2>This is a &lt;flink-mink&gt;</h2>
<flink-mink name="lit-html"></flink-mink>

  </div>
</section>
