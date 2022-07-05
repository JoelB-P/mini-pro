/* Universal Selector */
* {
  margin:0;
  padding:0;  
}

/* Element Selectors */
body {
  position: relative;
  font-family: "Goudy Bookletter 1911", sans-serif;
  font-size: 20px;
  background-color: rgb(20, 20, 99);
  color: rgba(255, 255, 255, 0.982);
  font-family: sans-serif;
}

h1,
h2 {
  margin: 20px;
}

main {
  padding: 60px 0;
}

li {
  display: inline;
  padding: 0px 20px;
  text-decoration: none;
}

a {
  text-decoration: none;
  color: #FDF8F5;
}

header,
footer {
  height: 60px;
  width: 100%;
  line-height: 60px;
  background-color: black;
}

header {
  position: fixed;
  border-bottom: 10px solid white;
}
.photo {
  width:200px; 
  display: block;  
  border-radius:50%; 
  margin-left: auto;
  margin-right: auto; 
}

footer {
  position: absolute;
  margin-top: 0;
  bottom: 0;
  border-bottom: 10px solid #4F4846;
  color: #FDF8F5;    
}

figure {
  margin-bottom: 40px;
}

img {
  display: block;
  margin: 20px auto;
}

section {
  margin-bottom: 0;
  padding: 20px 10px 40px 10px;
  border-top: 3px solid white;
  background-color:  black;
}

form {
  /* Center the form on the page */
  margin: 0 auto;
  width: 500px;
  padding: 10px;
  border: 5px solid white;
  border-radius: 20px;
}

label {
  display: inline-block;
  width: 100px;
}
  
input, 
textarea {
  box-sizing: border-box;
  width: 300px;
  border: 1px solid #4F4846;
}

textarea {
  vertical-align: top;
  height: 60px;
}
  
button {
  height: 40px;
  width: 120px;
  background-color: black;
  color: white;
  font-family: Georgia, 'Times New Roman', Times, serif;
}
 
/* Class Selectors */
.text-center {
  
  text-align: center;
}
footer {
  border-top: 3px solid white;
}

.text-right {
  text-align: right;
  font-family:Georgia, 'Times New Roman', Times, serif;
}
