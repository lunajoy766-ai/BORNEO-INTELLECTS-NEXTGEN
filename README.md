*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f7f4ef;
color:#333;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#8c7b68;
color:white;
position:sticky;
top:0;
}

nav ul{
display:flex;
gap:30px;
list-style:none;
}

nav a{
color:white;
text-decoration:none;
}

.hero{
height:80vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url(images/coworking.jpg);
background-size:cover;
color:white;
}

.hero h1{
font-size:55px;
margin-bottom:20px;
}

.btn{
padding:15px 35px;
background:#b08d57;
color:white;
text-decoration:none;
margin-top:20px;
border-radius:30px;
}

section{
padding:80px 10%;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:30px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 0 15px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h3{
padding:15px;
}

.card p{
padding:0 15px 20px;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
margin-top:30px;
}

.features div{
background:white;
padding:25px;
border-radius:10px;
text-align:center;
}

footer{
background:#8c7b68;
color:white;
text-align:center;
padding:30px;
}
