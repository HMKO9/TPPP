# TPPP
Give<!DOCTYPE html>
<html lang="fr">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>StudyAI - Révision IA</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Inter,Arial,sans-serif;
}

body{
    background:#f6f7fb;
    color:#111827;
}


/* NAVBAR */

nav{
    height:75px;
    background:white;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:0 60px;
    box-shadow:0 5px 20px #00000010;
}

.logo{
    font-size:28px;
    font-weight:800;
    color:#4f46e5;
}


nav a{
    text-decoration:none;
    color:#555;
    margin:0 15px;
    font-weight:600;
}


.btn{
    background:#4f46e5;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:12px;
    cursor:pointer;
}


/* HERO */

.hero{

    text-align:center;
    padding:80px 20px;

}


.hero h1{

    font-size:55px;
    max-width:900px;
    margin:auto;

}


.hero span{
    color:#4f46e5;
}


.hero p{

    margin-top:20px;
    color:#666;
    font-size:20px;

}


/* UPLOAD */


.upload{

    width:85%;
    max-width:900px;
    margin:40px auto;
    background:white;
    padding:50px;
    border-radius:25px;
    box-shadow:0 20px 40px #00000012;

}


.drop{

    height:230px;
    border:3px dashed #c7d2fe;
    border-radius:20px;

    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;

}


.drop h2{
    margin-bottom:15px;
}


.drop button{

    margin-top:20px;

}


/* DASHBOARD */


.container{

    width:90%;
    max-width:1200px;
    margin:50px auto;

}



.title{

    font-size:32px;
    margin-bottom:30px;

}


.cards{

    display:grid;
    grid-template-columns:repeat(3,1fr);
    gap:25px;

}


.card{

    background:white;
    padding:30px;
    border-radius:20px;

    box-shadow:0 10px 25px #00000010;

}


.card h2{

    color:#4f46e5;
    margin-bottom:20px;

}


.card p{

    color:#555;
    line-height:1.7;

}


/* QUIZ */


.quiz{

    margin-top:40px;

}


.option{

    background:#f1f5f9;
    padding:15px;
    margin:10px 0;
    border-radius:12px;
    cursor:pointer;

}


.option:hover{

    background:#e0e7ff;

}



/* FLASHCARD */


.flash{

    height:200px;

    background:#4f46e5;
    color:white;

    border-radius:20px;

    display:flex;
    align-items:center;
    justify-content:center;

    font-size:25px;
    font-weight:bold;

}


/* FOOTER */


footer{

    margin-top:80px;
    background:#111827;
    color:white;
    padding:40px;
    text-align:center;

}


/* MOBILE */


@media(max-width:800px){

nav{

    padding:20px;

}


nav div:nth-child(2){

    display:none;

}


.hero h1{

    font-size:35px;

}


.cards{

    grid-template-columns:1fr;

}

.upload{

    width:95%;

}

}


</style>


</head>



<body>


<nav>

<div class="logo">
    StudyAI
</div>


<div>

<a href="#">Accueil</a>
<a href="#">Cours</a>
<a href="#">Quiz</a>
<a href="#">Premium</a>

<button class="btn">
Connexion
</button>

</div>


</nav>




<section class="hero">


<h1>

Transforme tes cours en <span>révisions intelligentes</span> avec l'IA

</h1>


<p>

Upload ton cours et obtiens résumé, points clés, flashcards et quiz automatiquement.

</p>



</section>




<div class="upload">


<div class="drop">


<h2>
Dépose ton cours ici
</h2>


<p>
PDF • Word • Image
</p>


<button class="btn">
Importer un fichier
</button>


</div>


</div>





<div class="container">


<h1 class="title">
Dashboard étudiant
</h1>



<div class="cards">



<div class="card">

<h2>
Résumé IA
</h2>

<p>

L'intelligence artificielle permet de créer des systèmes capables d'effectuer des tâches nécessitant normalement une intelligence humaine.

</p>


</div>





<div class="card">

<h2>
Points clés
</h2>

<ul>

<li>Définition importante</li>
<li>Concepts principaux</li>
<li>Formules à retenir</li>
<li>Dates importantes</li>

</ul>

</div>




<div class="card quiz">

<h2>
Quiz
</h2>


<p>
Quel est le rôle principal de l'IA ?
</p>


<div class="option">
A - Remplacer Internet
</div>


<div class="option">
B - Automatiser des tâches
</div>


<div class="option">
C - Supprimer les cours
</div>


</div>



</div>





<br><br>



<div class="card">

<h2>
Flashcards
</h2>


<div class="flash">

Clique pour retourner

</div>


</div>



</div>






<footer>

StudyAI © 2026 - Apprendre plus vite avec l'IA

</footer>



</body>
</html>


 it all


