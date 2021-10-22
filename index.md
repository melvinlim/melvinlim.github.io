<head>
<!--
  <link rel="shortcut icon" type="image/x-icon" href="https://github.githubassets.com/favicons/favicon.svg">
-->

  <link rel="apple-touch-icon" sizes="180x180" href="/assets/images/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/images/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/images/favicon-16x16.png">
  <link rel="manifest" href="/assets/images/site.webmanifest">
  <link rel="mask-icon" href="/assets/images/safari-pinned-tab.svg" color="#5bbad5">
  <link rel="shortcut icon" href="/assets/images/favicon.ico">
  <meta name="msapplication-TileColor" content="#da532c">
  <meta name="msapplication-config" content="/assets/images/browserconfig.xml">
  <meta name="theme-color" content="#ffffff">

</head>

## Melvin Lim's portfolio

my attempts to create a portfolio

### Pages

<ul>
  {% assign mypages = site.pages | sort: "order" %}
    {% for page in mypages %}
    <li><a href="{{ page.url | absolute_url }}">{{ page.title }}</a></li>
    {% endfor %}
</ul>

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
markdown comment example

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
![Image](src)
```

[Play Tetris](tetris.html)

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/melvinlim/melvinlim.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

email: dxlim@outlook.com
