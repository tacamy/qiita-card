# qiita-card

## How to use

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="import" href="qiita-card.html">
</head>
<body>
  <qiita-card user="tacamy"></qiita-card>
</body>
</html>
```

## Options

### User ID

- attribute: `user`
- type: `String`
- requred

```html
<qiita-card user="tacamy"></qiita-card>
```

### Number of items

- attribute: `count`
- type: `Number`

```html
<qiita-card user="tacamy" count="3"></qiita-card>
```

### Width

- attribute: `width`
- type: `String` ("px" or "%")

```html
<qiita-card user="tacamy" width="300px"></qiita-card>
```

### Sort

- attribute: `sort`
- type: `String` ("stock" or "date")

```html
<qiita-card user="tacamy" sort="date"></qiita-card>
```

