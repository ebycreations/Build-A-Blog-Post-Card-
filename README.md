<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Post Card</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="blog-post-card">
<img src="https://cdn.freecodecamp.org/curriculum/labs/cover-photo.jpg" alt="cover photo" class="post-img">
<div class="post-content">
<h2 class="post-title">Coding Made Easy</h2>
<p class="post-excerpt">Learn how to code at your convenience while saving dollars.</p>
<a class="read-more" href="#">Read More</a>

</div>
</body>
</html>

** end of index.html **

** start of styles.css **

.blog-post-card{
  background-color: white;
  border-radius: 20px;
  width:350px;
  text-align: center;
  overflow: clip;
}

.post-img{
  width: 100%;
  border-bottom: 5px solid #333;
}

.post-content{
  padding: 20px;
}

.post-title{
  color: blue;
  margin: 0 0 10px 0
}

.post-excerpt{
  color: green;
  margin:0 20px
}

.read-more{
color: black;
background-color: yellow;
margin: 10px;
padding: 10px;
border-radius: 10px; 
display: inline-block
}

.read-more:hover{
  background-color: purple;
}
