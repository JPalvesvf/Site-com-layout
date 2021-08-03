# Site-com-layout
<!DOCTYPE html>
<html lang="pt-br">
<head> 
  <meta charset="utf-8">
 <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css">
<style>
 .ScrollspySite{
 Position: relative;
 overflow:auto;
 height:380px;
 }
 
 p {
  margin: 2;
  text-indent: 3ch;
  text-align: justify;}  
  
  
</style>
</head>
  
<body>
<div class="container">
    <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-info">
      <a class="navbar-brand text-white" href="#">Pokemon</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Alterna navegação">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class=" collapse navbar-collapse" id="navbarSite">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link text-white"  href="#"> Início <span class="sr-only">(Página atual)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link text-white" href="#">Pokédex</a>
      </li>
      <li class="nav-item ">
        <a class="nav-link text-white" href="#">Pokébolas</a>
      </li>

      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle text-white" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Pokemons
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Aerodactyl</a>
          <a class="dropdown-item" href="#">Blitzle</a>
          <a class="dropdown-item" href="#">Aimpom</a>
          <a class="dropdown-item" href="#">Torterra</a>
          <a class="dropdown-item" href="#">Shaymin</a>
        </div>
      </li>
    </ul>
  </div>
  
  
  <form class=" form-inline my-1 lg-0 text-white">
     <input class="form-control mr-sm-2" type="search text-white" placeholder="Pesquisar..." aria-label="Pesquisar">
     <button class=" text-white btn btn-outline-dark my-2 my-sm-0 " type="submit  ">Pesquisar </button>
   </form>
  </nav> 


<br><br>


<div id="carouselExampleControls" class="carousel slide" data-ride="carousel">
  <div class="carousel-inner"  interval="1000">
    <div class="carousel-item active">
       <img class="d-block w-100" src="Imagens/AerodactylBanner.png  "> 
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="Imagens/BlitzleBanner.png">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="Imagens/ShayminBanner.png">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="Imagens/TorterraBanner.png">
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="Imagens/AmbipomBanner.png">
    </div>
  <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Anterior</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Próximo</span>
  </a>
</div>

<br>

<div class="container">
  <div class="row mb-5">
    <div class="col-3"> 
     <nav id="list-example" class="list-group" >
       <nav class="nav nav-pills flex-colunn"> 
        
         <a class="list-group-item list-group-item-action" href="#list-item-1" >Aerodactyl</a>
          
         <a class="list-group-item list-group-item-action" href="#list-item-2">Blitzle</a>
         
         <a class="list-group-item list-group-item-action" href="#list-item-3">Aipom</a>
          
          <a class="list-group-item list-group-item-action" href="#list-item-4">Shaymin</a>
          
          <a class="list-group-item list-group-item-action" href="#list-item-5">Torterra</a>
       </nav>
     </nav>
    </div>
    
    <div class="col-9"> 
     <div data-spy="scroll" data-target="#list-example" data-offset="0" class="ScrollspySite">
       <h4 id="list-item-1"> <b> Aerodactyl </b> </h4>
       <p>Aerodactyl é um pterosaurian, Pokémon bípede com várias características dracônicas. Tem asas grandes e membranosas,
          bem como orelhas pequenas e pontiagudas, olhos estreitos, um focinho estriado, uma boca aberta e uma mandíbula forte cheia de presas serrilhadas. 
          Seu corpo é coberto por uma pele azul-acinzentada clara com membranas de asas violáceas. As asas do Aerodactyl consistem em uma membrana que vai da 
          lateral do corpo até a ponta de um dedo alongado. As mãos com garras no final de cada asa permitem que ele segure objetos. Possui uma crista em forma
           de corcunda com uma ponta no dorso e uma cauda forte com ponta em forma de flecha. Seus pés em forma de garra têm dois dedos na frente e um atrás e 
           são capazes de agarrar e agarrar firmemente sua presa durante o vôo.
          
      
      <h4 id="list-item-2"> <b> Blitzle </b> </h4>
      <p>Blitzle é um Pokémon preto semelhante a uma zebra com listras brancas de ponta dupla no pescoço, peito, costas e patas traseiras. Tem um focinho 
        arredondado com um nariz grande e escuro e olhos azuis ovais com escleras amarelas. No topo de sua cabeça estão orelhas curtas e triangulares com o
         interior azul. Abaixo dos joelhos, suas pernas são brancas com cascos pretos. Sua cauda é atarracada, branca e tem duas pontas. Subindo pelo pescoço
          está uma juba branca e pontiaguda, que culmina na frente em uma longa extensão que se assemelha a um raio. Esta juba captura e armazena eletricidade,
           que pisca sempre que o Pokémon descarrega energia. Ele se comunica com outros membros de sua espécie controlando o ritmo e a frequência desses flashes.
            Durante tempestades com raios, Blitzle se aventura para recarregar sua juba com raios.</p>
    

   
     <h4 id="list-item-3"> <b> Aipom </b> </h4>
     <p>Aipom é um Pokémon macaco com uma mão de três dedos no final de sua cauda. Seu pêlo é roxo, enquanto a pele de seu rosto, orelhas internas,
        barriga, pés, e a ponta de sua cauda é bege. Em seu rosto um sorriso muito alegres, olhos azuis e orelhas redondas. A cabeça do Aipom é 
        desproporcionalmente grande comparada ao seu corpo. Acima de sua cabeça há um topete que é mais longo em fêmeas do que em machos. Ao contrário de seus
        pés, os braços de Aipom são simples. Aipom usa sua cauda poderosa livremente e a usa para muitos propósitos. A cauda é forte o suficiente para pendurar
        Aipom em um galho e suspender o resto do corpo no ar, mas também delicada o suficiente para colher frutas e manipular objetos. Aipom vive alto nas 
        copas das árvores, usando a sua cauda para o manter o equilíbrio.</p>
        
        <h4 id="list-item-4"> <b> Shaymin </b> </h4>
        <p>Shaymin é um pequeno Pokémon branco parecido com um ouriço . Em Land Forme, possui pelo no dorso verde-relva e uma flor rosa com duas 
          folhas de cada lado da cabeça, que se assemelha à flor Gracidea . Várias flores semelhantes a Gracidea também aparecem em seu dorso sempre
           que se sente confortável, mas quando sente um perigo iminente, rapidamente o esconde. Suas pernas são curtas e sua parte inferior é 
           rechonchuda. Shaymin é o menor Pokémon Mítico até hoje e um dos menores Pokémon do tipo Grass.</p>
           
           <h4 id="list-item-5"> <b> Torterra </b> </h4>
           <p>Torterra é um Pokémon quadrúpede alto, volumoso, que se assemelha a uma tartaruga, com uma grande concha cobrindo suas costas. 
             Há uma única árvore semelhante a um carvalho e três extensões triangulares e rochosas que lembram picos de montanhas no topo da concha.
              Há uma mancha marrom, semelhante a solo, próximo à árvore. Uma borda branca envolve a concha e forma uma continuação em forma de 
              diamante na frente. O corpo de Torterra aparece seccionado, com a metade superior verde e a inferior marrom. Sua boca é recortada, 
              o que lhe dá a aparência de uma tartaruga agarradora. Ele também tem um nariz preto. Sua mandíbula inferior é verde e há duas grandes
               pontas projetando-se de suas bochechas. Os olhos pequenos e vermelhos de Torterra são circundados por um anel preto. Suas pernas são
                grossas e têm quatro dedos cada, que parecem na verdade pedras irregulares. Existem três dedos na frente e um no calcanhar.</p>


    
     </div>
    </div>
  </div>
</div>


<div class="card-deck" >
 <div class="card">
     <img class="card-img-top" src="Imagens/dex.jpg"  alt="Pokedex"> 
    
    <div class="card-body">
      <h5 class="card-title"><center><b>Pokédex e Informações </center> </b></h5>
    <a href="#"> <p class="card-text">Saiba Mais...</p> </a>
    </div>
  </div>
    
  <div class="card">
    <img class="card-img-top" src="Imagens/pokehere.png"  alt="Pokébola">
    <div class="card-body">
      <h5 class="card-title"> <b> <center> Cuidado com Pikachus à solta </center> </b></h5>
    <a href="#"> <p class="card-text" >Saiba Mais...</p> </a>
  </div>
  </div> 

<div class="card">
  <img class="card-img-top" src="Imagens/pokeic.jpg"  alt="Pokébola">
  <div class="card-body">
    <h5 class="card-title"> <b> <center> Pokebólas são necesárias? </center> </b></h5>
  <a href="#"> <p class="card-text" >Saiba Mais...</p> </a>
</div>
</div>


<div class="card">
    <img class="card-img-top" src="Imagens/Xpikachu.png"  alt="Proibido Pikachus">
    <div class="card-body">
      <h5 class="card-title"><b> <center> Pikachus são proibidos </center></b></h5>
    <a href="#"> <p class="card-text" >Saiba Mais... </p></a>
</div>
</div>

<div class="container">
  <div class="row">
    <div class="col-12 mb-3"><br></div>
    
    <div Class="col-sm-4">
      <h3 class="text text-center">Turma TII02</h3>
      <div align="justify"> Segunda turma em técnico de informática para internet do senai Uberaba</div>
    </div>
  
    <div Class="col-sm-4">
      <h3 class="text text-center">Menu</h3>
      <div class="btn-group-vertical btn-block btn-group-lg" role="group">
        <a class="btn btn-outline-primary" href"#">
          Pokemons
        </a>
        <a class="btn btn-outline-primary" href"#">
          Pokedex
        </a>
        <a class="btn btn-outline-primary" href"#">
          Pokebolas
        </a>
        <a class="btn btn-outline-primary" href"#">
          Pokestops
        </a>
      </div>
    </div>
    
    <div Class="col-sm-4">
      <h3 class="text text-center">Social Media</h3>
      <div class="btn-group-vertical btn-block btn-group-lg" role="group">
      <a class="btn btn-outline-primary" href"#">
        <i class="fa fa-facebook" aria-hidden="True"></i>
        Facebook
      </a>
      <a class="btn btn-outline-primary" href"#">
        <i class="fa fa-twitter-square" aria-hidden="True"></i>
        Twitter
      </a>
      <a class="btn btn-outline-primary" href"#">
          <i class="fa fa-instagram" aria-hidden="True"></i>
       Instagram
      </a>
      <a class="btn btn-outline-primary" href"#">  
        <i class="fa fa-whatsapp" aria-hidden="True"></i>
        Whatssap
      </a>
    </div>
  </div>
</div>
   <div class"col-12 mt-5">
     <blockquote classs="blockquote text-center">
     <center><i class="fa fa-copyright " aria-hidden="true" ></i> All rights reserved - 2021</center>
   </blockquote>
  </div>
</div>


<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
     <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
     <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</body>
