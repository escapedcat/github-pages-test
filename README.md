How come HTML structure looks like this?:

```html
  <body>
    <section class="page-header">
    </section>

    <section class="main-content">
    </section>
</body>
```

And not [like this](https://pages-themes.github.io/cayman/)?:

```html
<body cz-shortcut-listen="true">
    <a id="skip-to-content" href="#content">Skip to the content.</a>

    <header class="page-header" role="banner">
    </header>

    <main id="content" class="main-content" role="main">
    </main>
</body>
```
