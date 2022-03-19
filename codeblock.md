# Code Block
Sample of a simple code challange solved by me
### HTML
```html
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8" />
</head>
<body>
<script type="text/javascript">
var sum;
var i;
document.write("fizzbuzz", "<br>");
sum = 0;
for (i = 1; i < 100; i = i +1){
    if (i % 3 == 0 && i % 5 == 0){
        document.write("FIZZBUZZ", "<br>");
    }
    else if (i % 3 == 0){
        document.write("FIZZ", "<br>");
    }
    else if (i % 5 == 0){
        document.write("BUZZ", "<br>");
    }
    else{
        document.write(i, "<br>");
    }
}

</script>
</body>
</html>
```
[Return To Homepage](./README.md)
