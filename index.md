<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: cursive;
}

/* Style the header */
header {
  background-color: plum;
  padding: 3px;
  text-align: center;
  font-size: 35px;
  color: purple;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 15%;
  height: 400px; 
  background: #9370DB;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 0px;
  width: 85%;
  background-color: #FFE4E1;
  height: 400px; 
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both;
}

/* Style the footer */
footer {
  background-color: plum;
  padding: 20px;
  text-align: center;
  color: white;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}
</style>
</head>
<body>

<header>
  <h2 style="border:2px solid purple;">July By Noah Cyrus</h2>
</header>

<section>
  <nav>
    <ul>
      <li><a href="lyrics.txt">Lyrics</a></li>
	  <br>
      <li><a href="lyricsoutput.txt">Word Frequency</a></li>
	  <br>
	  <li><a href="lyricsinfo.txt">Info</a></li>
    </ul>
  </nav>

<img src = "wordcloud.png" width="600" height="400">
<style>
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
</style>

  </article>
</section>

<footer>
  <p>Created by Melonie Aminov</p>
  <p2>This webpage was developed for my data structures class in Brooklyn College.
      I have inserted a wordcloud made out of lyrics, attached the text
	  file with the lyrics, and included the word frequency list</p2>
</footer>

</body>
</html>

