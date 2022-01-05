# css-starter

Basic CSS resets and breakpoints for creating global stylesheets from scratch

Font sizes are assigned to h1, h2, h3, h4, and p elements AND classes. This allows elements to be styled independently of their semantic organization. Example:

```
<!-- Article ending with a card -->

<article>

  <h2>Article Title</h2>

  <p>Article Content...</p>

  <div class="card">

    <!-- h3 element with h4 font size -->

    <h3 class="h4">Card Title</h3>

    <p>Card Content...</p>

  </div>

</article>
```

These font sizes are assigned using rem. As viewport width increases, these font sizes are all scaled up together.

```
html {
  font-size: 100%
}

/* font sizes assigned to h1, h2, h3, h4 using rem /*

/* larger screen breakpoints */
html {
  font-size: 110%
}

/* etc... */
```
