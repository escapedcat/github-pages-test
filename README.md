## Question

How come HTML structure looks [like this](https://escapedcat.github.io/github-pages-test/)?:

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

According to [the latest `default` template of **cayman**](https://github.com/pages-themes/cayman/blob/master/_layouts/default.html#L25) it should use `header`, `main` and have a *scip to content* link.

## Answer
Because GH pages & offical theme preview always shows `master` branch.  
But GH pages is actually using the latest official version. In this case `0.1.1`.  
Confusing much? Yes!
