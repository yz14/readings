---
sort: 2
---

# Toasts Card

THIS IS TOO LONG, NEED UPDATE! HERE IS SOME IDEAS:

- https://primer.style/css/components/box
- https://primer.style/css/components/toasts

```note
## This is a note

Markdown is supported, Text can be **bold**, _italic_, or ~~strikethrough~~. [Links](https://github.com) should be blue with no underlines

`inline code`

[`inline code inside link`](./)
```

```note
This is note2
```

```note
This is note3
```

```tip
It’s bigger than a bread box.
```

```tip
It’s tip 2
```

```warning
Strong prose may provoke extreme mental exertion. Reader discretion is strongly advised.
```

```danger
Mad scientist at work!
```

type: custom:useful-markdown-card
style: |
  ha-card {
    padding: 16px;
  }
  h1 {
    text-align: center;
    font-size: 64px;
  }
  h2 {
    text-align: center;
    color: var(--primary-color);
  }
content: |
  # [[ sensor.time ]]
  ## [[ sensor.date ]]
