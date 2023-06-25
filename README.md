# Vue.js & Basil.css template

Minimal code example to show how Basil.css works with Vue.js.

### in main.ts
```
import "basilcss/basil.css"
```

### The template

```
<template>
  <section class="row m-2 vh-100 big:m-0 fade-in">
    <div class="col-8 big:col-4 big:flex-row-center-center">
      <img
        class="full-width big:w-60"
        src="https://images.pexels.com/photos/1437424/pexels-photo-1437424.jpeg?auto=compress&cs=tinysrgb&w=800"
        alt="image of a basil plant from pexels.com"
      />
    </div>
    <div class="col-8 big:col-4 big:flex-col-left-center">
      <h2 class="m-b-2 big:t-left big:w-70">Basil.css and Vue.js</h2>
      <p class="m-b-2 big:t-left big:w-70">
        By using Basil you speed up your development by only sprinkling the bare
        minimum of basil on your spaghetti code. Basil only uses CSS grids,
        flexbox, fontsize, margin, padding and media queries. That leaves you to
        style the rest of the app with whatever CSS method you want.
      </p>
      <a class="m-b-2 full-width big:w-30" href="https://basilcss.com">
        <button class="btn-primary m-b-2 full-width big:w-90">
          Try Basil CSS
        </button>
      </a>
    </div>
  </section>
</template>
```
