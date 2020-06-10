<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp"
    crossorigin="anonymous">
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
    crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <title>Portfolio</title>
</head>
<body>
<!-- Content -->



<!-- Jumbotron -->
    <div id= "jumbotron">
        <div class="dark-overlay">
        <!-- Navbar -->
            <nav class="navigation fixed-top">
                <div class="case mx-5">
                    <a href="#" class="brand"><span class="logo-design">&lt;/</span>clsn<span class="logo-design">&gt;</span></a> 

                   
                       <ul class="nav">
                           <li class="navitem"><a href="#" class="navlink ml-5">About</a></li>
                           <li class="navitem"><a href="#" class="navlink ml-5">Contact</a></li>
                       </ul>
                   
                </div>
            </nav>
        <!-- Jumbotron Text -->
            <div class="col-lg jumbotron-text text-center">
                <h1 class="display-3 text-center">
                    <span id="web-developer">Aspiring Web Developer</span>
                </h1>
                <p class="jumbotron-subtitle mt-5">Hi, my name is <span class="orange">Saimon</span>.</p>
            </div>
        </div>
    </div>

    <main>
        <!-- Transition -->
        <div class="who-section bg-light">
          <div class="who-section-text text-center col">
            <h1 class="">Hi, I'm Saimon</h1>
          </div>
        </div>

        <!-- Credentials -->
       <div class="credentials-section bg-light">
        <div class="container py-4">
          <div class="card-columns">

            <div class="card text-center ">
                <div class="card-header bg-warning text-light">
                  <h2>About Me</h2>
                </div>
              <div class="card-body bg-light">
               <div class="card-title">
                 I'm Saimon Robert L. Cachuela, currently, a 2nd Year Computer Engineering student at Polytechnic University of The Philippines. 
                </div>
              </div>
            </div>

            
            <div class="card text-center ">
              <div class="card-header bg-danger text-light">
                <h2>Skills</h2>
              </div>
            <div class="card-body bg-light">
             <div class="">
              I can build simple web apps like, To do list and Photo Gallery using Laravel Framework
              </div>
            </div>
          </div>

          <div class="card text-center ">
            <div class="card-header bg-info text-light">
              <h2>Contacts</h2>
            </div>  
          <div class="card-body bg-light">
           <div class="card-title">
            <p>cachuelasaimon@gmail.com</p>
            

            </div>
          </div>
        </div>

          
            
          </div>
        </div>
       </div>

      <!-- Projects -->
      <div class="who-section bg-warning">
        <div class="who-section-text text-center col">
          <h1 class="">Things I've done</h1>
        </div>
      </div>

      <div class="project-section bg-warning">
        
     <div class="container">
       <div class="row">
          <img src="img/ToDoList.png" alt="" class="col-lg-4  mb-4">
          <img src="img/ToDoList_2.png" alt="" class="col-lg-4  mb-4">
          <img src="img/Client_list.png" alt="" class="col-lg-4  mb-4">
      </div>

      <div class="row">
        <img src="img/Client_List_2.png" alt="" class="col-lg-4  mb-4">
        <img src="img/Photo_Gallery.png" alt="" class="col-lg-4  mb-4">
        <img src="img/Photo_Gallery_2.png" alt="" class="col-lg-4  mb-4">
    </div>
      
      
        
      
   </div>
      </div>
        

    </main>



 <!-- JavaScript Inlclusions -->
 <script src="http://code.jquery.com/jquery-3.3.1.min.js" integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="
 crossorigin="anonymous"></script>
   <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
     crossorigin="anonymous"></script>
   <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T"
     crossorigin="anonymous"></script>

     <script type="text/javascript">
        $(document).ready( function () {
          $(window).on('scroll', function () {
              
              if($(window).scrollTop()) {        
                $('.navigation').addClass('scrolled');
              } else {
                $('.navigation').removeClass('scrolled');
              }
          })
        });
    </script>
 
    </body> 
