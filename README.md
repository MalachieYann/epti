<!DOCTYPE html>
<html>

    <head>
        <meta charset="utf-8">
        <title>EPTI</title>
        
        <link rel="stylesheet" href="Index.css"></link>

        <style>
        *{
          padding: 0px;
          margin:0px;
      }
      nav{
          background-color: #1E90FF;
          height: 50px;
      }
      
      nav ul{
          height: 50px;
          width: 500px;
          margin: 0 auto;
      }
      
      nav ul li{
          list-style-type:none;
          width: 100px;
          float: left;
          text-align: center;
      }
      
      li a{
          text-decoration: none;
          color:white;
          line-height: 50px;
          display: block;
      }
      
      li a:hover{
          background-color:skyblue;
          color: aliceblue;
      }
          
      body{
          background-image:url(2.jpg);
          background-repeat: no-repeat;
          background-attachment: fixed;
          background-size: 100% 100% ;
      }
      
      img{
          width: 250px;
          padding: 0px;
      }
      
      h1{
          color:#1E90FF;
          font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
          text-align: center;
          font-size: 40px;
          margin:70px;
          padding:60px ;
          background-color: white;
          margin-top: -20px;
          margin-left: 350px;
          margin-right: 350px;
          filter: opacity(80%);
      }
      
      h3{
          text-align: center;
          font-size:50px ;
          margin: 70px;
          padding: 60px;
          font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
          color:#1E90FF; 
          margin-top: -80px;
      }
      
      h4{
          color:#1E90FF;
          font-size: 30px;
          text-align: center;
      }
      
      p{
          font-size: 30px;
          background-color: white;
          font-family:Arial, Helvetica, sans-serif;
          filter: opacity(80%);
      }   
      
      ol li{
          font-size: 25px;
          color: black;
          padding: 5px;
          margin-left: 35px;
          font-family:Georgia, 'Times New Roman', Times, serif;
          background-color: beige;
          filter:opacity(60%);
        }

        form{
  text-align: center;
  background-color:#fff;
}
        </style>
        </head>
        <body>
            <nav>
                <ul>
                    <li><a href='#'>Accueil</a></li>
                    <li><a href='#'>Presentation</a></li>
                    <li><a href='#'>Nos Services</a></li>
                    <li><a href='#'>Contacts</a></li>
                    <li><a href='#'>S'inscrire</a></li>
                </ul>
             </nav>
            
             <img src="EPTC-1.png">
             <h1><u>EUROKA PROFESSIONNAL TRANING CENTER</h1>
             <h3><u>Centre de formation professionelle & continue</u></h3>

             <h4><u>Qui sommes nous ?</u></h4>
             <br>
             <p> Nous sommes un cabinet d’études et d'accompagnement, regroupant plusieurs experts au plan international et qui se donne pour objectif de contribuer à travers un service de qualité, à l’amélioration de la performance globale des organisations et entreprises publiques comme privées, en les outillant pour une meilleure atteinte des résultats qu’elles se seront fixés notamment grâce a:
             </p>
                <br>
                <ol type="a">
                    <li>A un réseau de partenaires très expérimentés ayant la confiance de grands groupes internationaux.</li>
                    <li>Le niveau d’excellence de nos collaborateurs.</li>
                    <li>Un riche réseau d’experts internationaux  et nationaux ayant au moins 20 ans d’expériences dans leurs domaines d’intervention</li>
                    <li>Des solutions innovantes et des services porteurs de valeur ajoutée.</li>
                    <li>Des destinations aux choix ainsi que des centaines de modules et problématiques proposés.</li>
                    <li> Des thématiques sur mesures adaptées à vos besoins.</li>
                </ol>
                <form>
                  <form name="inscription" method="post" action="">
                      <fieldset>
                         <legend><h2>Inscription</h2></legend>
                         Civilité<br>
                         <input type="radio" name="civilite"> Mlle<br>
                         <input type="radio" name="civilite"> Mme<br>
                         <input type="radio" name="civilite"> M.<br>
                         Nom et prénom<br>
                         <input type="text" name="nom" value=""><br>
                         Email<br>
                         <input type="text" name="Contact" value=""><br>
                         Contact<br>
                         <input type="text" name="Ville" value=""><br>
                         Ville<br>
                         <input type="text" name="Pays" value=""><br>
                         Pays<br>
                         <input type="text" name="date de naissance" value=""><br>
                         date de naissance<br>
                         <input type="password" name="pass" value=""><br>
                         Vous être<br>
                         <select name="niv">
                            <option>Etudiant</option>
                            <option>Fonctionnaire</option>
                            <option>Employé au secteur privé</option>
                         </select><br>
                         <input type="button" name="envoyer" value="S'inscrire">
                      </fieldset>
                   </form>
                 </form>
        </body>
<strong>davenjc <i></i></strong>
    </head>

</html>
