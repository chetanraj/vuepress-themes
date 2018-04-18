---
sidebar: auto
---

# VuePress Themes

> Simple Vuepress Theme Override Stylus

Vuepress by default ships with default theme, you can create an override of the default theme by creating a ```.vuepress/override.styl``` file and copy the stylus syntax into the ```override.styl``` file.

## Default Theme
```
$accentColor = #3eaf7c
$textColor = #2c3e50
$borderColor = #eaecef
$codeBgColor = #282c34
```

## Material Light Theme
```
$accentColor = #009688
$textColor = #212121
$borderColor = #bdbdbd
$codeBgColor = #fff
```

## Material Dark Theme
```
$accentColor = #009688
$textColor = #212121
$borderColor = #bdbdbd
$codeBgColor = #fff

html, body , .navbar, .sidebar {
  background-color: #263238;
}

.theme-container .navbar,
.theme-container .sidebar {
  background-color: #263238;
}

.theme-container .search-box input,
.theme-container .search-box .suggestion a {
  color: #009688;
}

.theme-container .content code {
  background-color: #2e3d44;
}

```
