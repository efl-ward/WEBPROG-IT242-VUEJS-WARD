
<!DOCTYPE html>
<html>
<head>
  <title>My first Vue page</title> 
 <link rel= "stylesheet" href="css/style.css?version=0.1">
 <link rel="stylesheet" href="css/style2.css?version=0.1">
</head>
<body>

<h1>Vue Example</h1>

<p>The message is taken from 'data' inside the Vue instance by writing {{ message }} inside the div with id="app".</p>

<div id="app">
  {{ message }}
</div>

<h1>Personal Profile Web page </h1>
<p>
 
About Me<br>
Name: Eduard Florence L. Serna<br>
 
Education<br>
Elementary:Kapitan Jose Cardones Memorial Elementary School<br>
Junior Highschool: Signal Village National High School<br>
Senior Highschool: Learn & Explore Montessori School<br>
College: Asia Pacific College<br>
Course: IT<br>
IT Experience: UI/UX, SQL, Python, Java,  <br>
Hobbies & Interests: Playing Games, Listening to music, Reading Manga & Manhwa<br>
Goals In Life / Dream: To become a rich millionare tito<br>
Picture Gallery<br>
 <div class="container">
  <div><img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Oceanogr%C3%A0fic_29102004.jpg" alt="Me" width="100" height="100"></div> 
  <div><img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Oceanogr%C3%A0fic_29102004.jpg" alt="Me" width="100" height="100"></div> 
  <div><img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Oceanogr%C3%A0fic_29102004.jpg" alt="Me" width="100" height="100"></div> 
  <div><img src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Oceanogr%C3%A0fic_29102004.jpg" alt="Me" width="100" height="100"></div>    
</div>
</p>

<div id="app">
  {{ message }}
</div>

<div id="app2">

  <div>
    <img v-for="x in manyFoods" v-bind:src="x">
  </div>

</div>

<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>

<script src="js/vue.js"></script>

<script src="js/vue2.js"></script>

</body>
</html>
