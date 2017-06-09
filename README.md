<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>JS Bin</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/marked/0.3.6/marked.js"></script>
  <link rel="stylesheet" href="https://typo.sofi.sh/typo.css">
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
  <style>
  body{
    padding:26px
  }
  img{
    max-width:100%
  };
  </style>
</head>
<body>
<div id="content"></div>
  <script>
var markdown =`
# 我的第一篇博客
**芳芳**
>dsasdd

ddddd

[百度](http://baidu.com)


<img src="http://pic23.nipic.com/20120903/10422454_211025593122_2.jpg" >
`

var html=marked(markdown);
console.log(html);
    document.getElementById('content').innerHTML =
      html;
  </script>
</body>
</html>
