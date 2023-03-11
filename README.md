 
 page 1 /html
 
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITC TALK's</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
</head>
<body>
    
     

        <header>

            <div class="dropdown">
                <button class="dropbtn"> 
                     <span class="material-symbols-outlined" id="menu">
                         menu
                     </span>
                    
                </button>
                <div class="dropdown-content">

                    <a href=" file:///C:/Users/badi/Desktop/Nouveau%20dossier%20(10)/its%20talks/index.html">Home</a>
                    <a href=" file:///C:/Users/badi/Desktop/Nouveau%20dossier%20(10)/its%20talks/page2.html">What is ITC COMMUNITY ?</a>
                   
                </div>
            </div>

           

            <img src="image/logo.png" alt="" class="logo">
        </header>

        <div class="home-page">

            <div class="box-1">

                <h1 class="h1-1">Welcome to ITC TALk's 4th editions <br>
                    reserve your place now

                 </h1>

                 <button class="btn-1"> <a href="http://docs.google.com/forms/d/e/1FAIpQLSe9_Ja2lrtydXsxP1fePtwfe7JiMThVLwIOktDb-m93A-Qo9g/viewform" target="_blank" rel="noopener noreferrer">Register here</a></button>


            </div>
          

            <div class="box-2">
                <h2>What is ITC TALK ? :</h2>
            </div>
            
            
            

            <div class="box-3">

                 <p>

                    It's an annual event organized by the club IT community , this year it will take place in SAAD DAHLEB Blida 1 the <br>
                    15th of March Creative and competent personalities will join us and make conferences about their fields. Every <br>
                    speaker will have his own part, they will talk about their starts, successes, achievements, personal experiences in <br>
                    the field, advices... And we will also organize several talks and discussions on various topics, where people can <br>
                    expand their knowledge and grow as persons in a fun way and a familial, wonderful atmosphere.
                 </p>

                 <h3>Don’t miss the opportunity to join us ! </h3>

                <div class="countdown">

                      <h1 id="countdown"></h1>
                      <span class="material-symbols-outlined" id="timer">
                        schedule
                        </span>

                </div>



            </div>

            <div class="box-4">

                <div class="location">
                    <span class="material-symbols-outlined">
                        location_on
                        </span>
                        <p>saad Dahlab university</p>

                </div>

                <div class="date">
                    <span class="material-symbols-outlined">
                        date_range
                        </span>
                        <p>Wednesday,March 15th,2023</p>
                </div>





            </div>





        </div>

        <footer>
            <p class="p-c">Contact US :</p>

            <div class="box-5">

            <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer"><img src="image/instagram.png" alt="" class="ft-2"></a>
            <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer"> <p>IT Community</p></a>
             
            </div>
             
            <div class="box-5">
              <a href="https://www.facebook.com/itc.blida.1" target="_blank" rel="noopener noreferrer"><img src="image/icons8-facebook-50 (1).png" alt="" class="ft-1"></a>
              <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer">  <p>Itc Blida</p> </a>
             
             
            </div>
           
      

        </footer>

   





  <script src="script.js"></script>
</body>
</html>


page 1/ css


*{
    margin: 0;
    padding: 0;
    box-sizing: none;

}

  body{
    background-image: url("image/home\ page\ -\ 1.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    
    width: 100%;
     
    
}


header{

    height: 10vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    
  

}


.logo{

    height:  80%;
    width:  8em;
    padding: 1%;

}


#menu  {

    
    padding: 2%;
    cursor: pointer;
       
}


.dropbtn {
    background-color:  transparent;
    color: rgb(0, 0, 0);
    padding: 16px;
    font-size: 16px;
    border: none;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: lightgrey;
    min-width: 200px;
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {background-color: white;}
.dropdown:hover .dropdown-content {display: block;}
 


.home-page{
    
    display: flex;
    flex-direction: column;
    
    
     


}


.box-1{

     height: 40vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content:  space-between ;
   padding: 10%;
    
    

    
}


.h1-1{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: 500;
    text-align: center;
    font-size: 40px;
}


.btn-1{
  

background-color: #D30B0B;
color: #fff;
border-radius: 38.3726px;
border: none;
padding: 12px;
font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: 700;
    box-shadow: 2.019608974456787px 6.0588274002075195px 6.0588274002075195px 0px #00000040;

    cursor: pointer;
     text-decoration: none;

     
    
}

a{
    text-decoration: none;
    color: #fff;
    font-size: 21px;
}


.btn-1:hover{
    transform: scale(1.1);
}

h2{
    padding-left: 1.5%;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: 400;
    font-size: 30px;
}


.box-3{

    height: 50vh;

    display: flex;
     flex-direction: column;
     justify-content: space-between; 
     align-items: center;
     padding: 3% 10%;




}





p{

    text-align: center;
    font-size: 20px;
    font-weight: 400;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


h3{

    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-size: 26px;
    font-weight: 400;
}
 

.countdown{

     padding: 2%;
    border: 4px solid #D30B0B;
    border-radius: 46px;
    display: flex;
    align-items: center;
    justify-content: center;
  
     
}

#countdown{
    font-size: 22px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


.countdown:hover{
     transform: scale(1.1);
     cursor: pointer;
     border: 4px solid  #00142E;
     background-color:  #00142E;
     color: #fff;
}


 



.box-4{


     height: 10vh;
    display: flex;
    flex-direction: column;
    
    justify-content: space-between;
     

    padding: 2%;

}

.location{
    display: flex;
    flex-direction: row;
    align-items:  center;
    justify-content: start;
    color: #00142E;
}
 
.date{
    color: #00142E;
    display: flex;
    flex-direction: row;
    align-items:  center;
    justify-content: start;

}


footer{
    height: 20vh;
    width: 100%;
    background-color:   #D30B0BB8;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: start;
    padding: 0 2% ;
    
}

.p-c{
    color: white;
}


.box-5{

    display: flex;
 
    align-items: start;
    width: 20%;
     cursor: pointer;
    color: #00142E;
     
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


.box-5 p{
    
    color: #00142E;
}


.ft-1{
    color: #00142E;
    height: 30px;
    width: 30px;
    cursor: pointer;
     
}


.ft-2{
    color: #00142E;
    height: 30px;
    width:30px;
    cursor: pointer;
}



page2 / html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITC TALK's</title>
    <link rel="stylesheet" href="style2.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
</head>
<body>
    <header>

        <div class="dropdown">
            <button class="dropbtn"> 
                 <span class="material-symbols-outlined" id="menu">
                     menu
                 </span>
                
            </button>
            <div class="dropdown-content">

                <a href=" file:///C:/Users/badi/Desktop/Nouveau%20dossier%20(10)/its%20talks/index.html">Home</a>
                <a href=" file:///C:/Users/badi/Desktop/Nouveau%20dossier%20(10)/its%20talks/page2.html">What is ITC COMMUNITY ?</a>
               
            </div>
        </div>

       

        <img src="image/logo.png" alt="" class="logo">
    </header>

   <div class="home-page">

    <h1> What is ITC COMMUNITY ? </h1>

    <p>
        ITC is a scientific club in univercity of saad dahleb blida 1 created to improve <br>
        the knowledge and skills of each member for better personal development <br>
        under the slogan
    </p>

    <h2>Sharing Is <span class="sp-1">Caring</span> </h2>

    <img src="image/itc talks 31.jpg" alt="">


   </div>

   <footer>
    <p class="p-c">Contact US :</p>

    <div class="box-5">

    <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer"><img src="image/instagram.png" alt="" class="ft-2"></a>
    <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer"> <p>IT Community</p></a>
     
    </div>
     
    <div class="box-5">
      <a href="https://www.facebook.com/itc.blida.1" target="_blank" rel="noopener noreferrer"><img src="image/icons8-facebook-50 (1).png" alt="" class="ft-1"></a>
      <a href="https://www.instagram.com/it_community/" target="_blank" rel="noopener noreferrer">  <p>Itc Blida</p> </a>
     
     
    </div>
   


</footer>




</body>
</html>

page2/ css
*{
    margin: 0;
    padding: 0;
    box-sizing: none;

}

  body{
    background-image: url("image/home\ page\ -\ 1.png");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    
    
    width: 100%;
     
    
}


header{

    height: 10vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    
  

}


.logo{

    height:  80%;
    width:  8em;
    padding: 1%;

}


#menu  {

    
    padding: 2%;
    cursor: pointer;
       
}


.dropbtn {
    background-color: transparent;
    color: rgb(0, 0, 0);
    padding: 16px;
    font-size: 16px;
    border: none;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: lightgrey;
    min-width: 200px;
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {background-color: white;}
.dropdown:hover .dropdown-content {display: block;}
 

.home-page{
    
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    height: 120vh;
    width: 100%;
    padding-bottom: 20%;

}

h1{
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: 500;
    text-align: center;
    font-size: 40px;
}

p{

    text-align: center;
    font-size: 20px;
    font-weight: 400;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

h2{
    text-align: center;
    font-size: 35px;
    font-weight: 400;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;

}

.sp-1{
    color:#D30B0B ;
}


img{
    height: 40%;
    width: 40%;
}



 
footer{
    height: 20vh;
    width: 100%;
    background-color:   #D30B0BB8;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: start;
    padding: 0 2% ;
    
}

.p-c{
    color: white;
}


.box-5{

    display: flex;
 
    align-items: start;
    width: 20%;
     cursor: pointer;
    color: #00142E;
     
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


.box-5 p{
 
    color: #00142E;
}


.box-5 a{
    text-decoration: none;
}


.ft-1{
    color: #00142E;
    height: 30px;
    width: 30px;
    cursor: pointer;
     
}


.ft-2{
    color: #00142E;
    height: 30px;
    width:30px;
    cursor: pointer;
}




