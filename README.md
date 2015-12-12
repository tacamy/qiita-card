# &lt;qiita-card&gt;

`<qiita-card>` is a custom element to display user contributions on [Qiita](http://qiita.com).

## How to use

Import `qiita-card.html` and put `<qiita-card>` tag on your HTML.

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="import" href="qiita-card.html">
  </head>
  <body>
    <qiita-card user="qiita"></qiita-card>
  </body>
</html>
```

## Options

| Attribute | Type | Default | Required | Description |
|---|---|---|:---:|---|
| `user` | `String` | - | ✔ | User ID on [Qiita](http://qiita.com) |
| `count` | `Number` | `3` | - | Display count of Item |
| `sort` | `String` | `stock` | - | Display order by `stock` or `date` |

```html
<qiita-card
  user="qiita"
  count="3"
  sort="stock">
</qiita-card>
```

## License

MIT © tacamy
