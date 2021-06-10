# Isolated-Bootstrap-5
If you decided to use Bootstrap in several places of your site but including Bootstrap CSS rewrites your styles in other places you should use this CSS files to isolate Bootstrap CSS.
<h2>Usage</h2>
<ol>
  <li>Replace the Bootstrap css link.</li>
</ol>
<h6>Original</h6>

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
```
<h6>Isolated</h6>

```html
<link href="https://raw.githubusercontent.com/onderakbulut/Isolated-Bootstrap-5/main/bootstrap-5.0.1-iso.css">
```

<ol start="2">
  <li>Create <code>div</code> element with <code>class="bootstrap-iso"</code> where you want to use Bootstrap styles.</li>
  <li>It's ready to use:</li>
</ol>

```html
<div class="bootstrap">
    <!-- Bootstrap works only here-->
</div>
```
