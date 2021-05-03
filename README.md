<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Salma El arabi</title>
    <link rel="stylesheet" href="css/styles.css">
    <img class='img/Salma El arabi.png'>
    <H1>
        MON PORTFOLIO
    </H1>

</head>
<body>

    <!-- HAUT DE PAGE -->

    <!-- MENU DE NAVIGATION -->
     <nav class="menu-nav">
    <ul>       
    <li class= "btn">
        <a href="monparcours.html">
        Mon parcours
    </a>
</li>
    <li class="btn"><a href="contactez-moi.html">
        Contactez-moi
    </a>
</li>
    </ul>  
    </nav> 
    <!-- CONTENUE SOUS FORME DE BOITE -->
    <div id="content">
    </div>
        
    <div class="leftbox"> 
    </div> 
        <H2>
            Mes projets
        </H2>
      <img src="img/tableaupaysage.jpg" alt=""width="40%"/>  
      <iframe src="https://scratch.mit.edu/projects/510456116/embed" allowtransparency="true" width="480" height="400" frameborder="0" scrolling="no" allowfullscreen></iframe>
    <div class="rightbox">
    </div>
    <H2>
        Mes sites réalisés
    </H2>
   <img src="img/Captureb.PNG" alt=""width="60%"/>  
   <img src="img/Captureg.PNG" alt=""width="60%"/>  

    <!-- PIED DE PAGE -->
    <footer>
     <p>
         Copyright &copy; Gravenilvec - 2020-2021 - All Right Reserved    
     </p>   
    </footer>
</body>
</html>

CSS

H1{
    padding-left: 50%;
}
nav.menu-nav ul li.btn{
    display: inline-block;
    list-style-type: none;
}
nav.menu-nav ul li.btn a{
    text-decoration: none;
    padding: 100px;
}
nav.menu-nav ul li.btn:hover a{
    color:rgb(189, 147, 93); 
    transition: 0.3s all;
}   

div#content div.rightbox{
    width: 100%;
    margin: 8px;
}
footer{ 
    background-color: rgb(189, 147, 93);
}
