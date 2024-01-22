# Commands

## Using the `sp` command

?>`sp <your/path/here>`.

!> Note: If you want to use an absoulute path use a `/` at the front for example:

```Helix
sp /your/path/here
``````
<!-- prettier-ignore-start -->
```html
<!-- compressed -->

<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/vue.css" />
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/buble.css" />
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/dark.css" />
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/pure.css" />
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/lib/themes/dolphin.css" />
```
<!-- prettier-ignore-end -->

If you have any ideas or would like to develop a new theme, you are welcome to submit a [pull request](https://github.com/docsifyjs/docsify/pulls).

#### Click to preview

<div class="demo-theme-preview">
  <a data-theme="vue">vue.css</a>
  <a data-theme="buble">buble.css</a>
  <a data-theme="dark">dark.css</a>
  <a data-theme="pure">pure.css</a>
  <a data-theme="dolphin">dolphin.css</a>
</div>

<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  const preview = Docsify.dom.find('.demo-theme-preview');
  const themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    const title = e.target.getAttribute('data-theme');

    themes.forEach(theme => {
      theme.disabled = theme.title !== title;
    });
  };
</script>

## Other themes

- [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/) A delightfully simple theme system for docsify.