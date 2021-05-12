---
theme: none
layout: cover
company: COMPANY NAME
date: 12.05.2021
---
# PRESENTATION COVER TITLE
##### Insert the sub title of your presentation
### Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua

---
layout: content-1
---
# Content

Content subtitle

- Content bullet text
- Content bullet text
- Content bullet text
- Content bullet text
- Content bullet text
- Content bullet text

<br>
<br>

Some text with [link](#)

---
layout: section-1
---

# SECTION BREAK SLIDE TITLE

Section break slide text

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
---
layout: section-2
---

# SECTION BREAK SLIDE TITLE

Section break slide text

[Documentations](https://sli.dev) / [GitHub Repo](https://github.com/slidevjs/slidev)
---
layout: content-2
---
# TABLE

Table text

### Table description

|     |     |
| --- | --- |
| <kbd>item kbd</kbd> / <kbd>item kbd</kbd> / <kbd>item kbd</kbd> | row text, row text, row text, row text |
| <kbd>item kbd</kbd> | row text |
| <kbd>item kbd</kbd> | previous slide |
| <kbd>item kbd</kbd> | next slide |

---
layout: image-side
image: 'https://source.unsplash.com/collection/94734566/1920x1080'
---

# CODE EXAMPLE

Code description

```ts
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: Partial<User>) {
  const user = getUser(id)
  const newUser = {...user, ...update}  
  saveUser(id, newUser)
}
```

---
layout: end
---

# Thanks!

Some text
