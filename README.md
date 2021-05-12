# slidev-theme-zhozhoba

[![NPM version](https://img.shields.io/npm/v/slidev-theme-zhozhoba?color=3AB9D4&label=)](https://www.npmjs.com/package/slidev-theme-zhozhoba)

A zhozhoba theme for [Slidev](https://github.com/slidevjs/slidev).

This theme is inspired by the Basic Black/White theme:
light theme            |  dark theme
:-------------------------:|:-------------------------:
![light](.github/light.png)  |  ![dark](.github/dark.png)


<!--
run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
put some screenshots here to demonstrate your theme,
-->

<!-- 
Live demo: [...]
-->

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>zhozhoba</b>
---</code></pre>

Learn more about [how to use a theme](https://sli.dev/themes/use).

## Layouts

This theme provides the following layouts:
---
### Cover
Usage: 
```
---
theme: zhozhoba
layout: cover
company: COMPANY NAME (optional)
date: 12.05.2021 (optional)
---
```
<div align="center">
  <img src="./slides-export/01.png" alt="cover">
</div>

---

### Content-1
Usage: 
```
---
layout: content-1
---
```
<div align="center">
  <img src="./slides-export/02.png" alt="content-1">
</div>

---

### Section-1
Usage: 
```
---
layout: section-1
---
```
<div align="center">
  <img src="./slides-export/03.png" alt="section-1">
</div>

---

### Section-2
Usage: 
```
---
layout: section-2
---
```
<div align="center">
  <img src="./slides-export/04.png" alt="section-2">
</div>

---

### Content-2
Usage: 
```
---
layout: content-2
---
```
<div align="center">
  <img src="./slides-export/05.png" alt="content-2">
</div>

---

### Image
Usage: 
```
---
layout: image-side
image: 'image-url'
---
```
<div align="center">
  <img src="./slides-export/06.png" alt="image">
</div>

---

### End
Usage: 
```
---
layout: end
---
```
<div align="center">
  <img src="./slides-export/07.png" alt="end">
</div>

---


## Contributing

- `npm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to genreate the preview PDF
- `npm run screenshot` to genrate the preview PNG
