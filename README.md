#Pixiv Ranking in php

####Feature

- Grab & show pixiv pictures in ranking.
- Customize rank numbers.
- Customize modes of ranking.

####Usage

Directly use the file as a picture.
```html
<img src="web/path/to/pixiv.php">
```

```css
body {background-image: url(/web/path/to/pixiv.php);}
``` 

Also try parameter `num` and `mode`.
```html
<img src="web/path/to/pixiv.php?num=4&mode=monthly">
``` 
####Parameter

- Parameter `num` in range from 0 - 49 which means rank #1 - #50.

- The mode name is even with official website.

| Mode List | 
| ----- |
| Daily |
| Weekly |
| Monthly |
| Rookie |
| Original |
| Male |
| Female |