# qiita-card

The `<qiita-card>` is one of blog parts of next generation.

This uses following technologies.

- WebComponents
- ES2015 (ES6)
- [Fetch API](https://fetch.spec.whatwg.org/)

## How to use

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

### User ID

- attribute: `user`
- type: `String`
- requred

```html
<qiita-card user="qiita"></qiita-card>
```

### Number of items

- attribute: `count`
- type: `Number`

```html
<qiita-card user="qiita" count="3"></qiita-card>
```

### Width

- attribute: `width`
- type: `String` (`"px"` or `"%"`)

```html
<qiita-card user="qiita" width="250px"></qiita-card>
```

### Sort

- attribute: `sort`
- type: `String` (`"stock"` or `"date"`)

```html
<qiita-card user="qiita" sort="stock"></qiita-card>
```
