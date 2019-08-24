<!DOCTYPE html>
<html>
<head>
 
    <meta charset="utf-8">
    <title>First Website</title>
  <style>
      *{
          margin:0;
          padding:0;
          font-family:'Century Gothic', monospace;
      }
      header{
          background-image:linear-gradient(rgba(0,0,0,0.5),rgba(0,0,0,0.5)),url(wallpaper.jpg);
          height:100vh;
          background-size: cover;
          background-position: center;
      }
      ul{
          list-style-type: none;
          float:right;
          margin-top: 25px;
      }
      ul li{
          display: inline-block;
      }
      ul li a{
          text-decoration: none;
          color:#fff;
          padding: 5px 20px;
          border: 1px solid transparent;
          transition: 0.6s ease;
      }
      ul li a:hover{
          background-color: #fff;
          color:#000;
      }
      ul li.active a{
             background-color: #fff;
          color:#000;
      }
      .logo img{
          float:left;
          width:150px;
      }
      .main{
       max-width: 1500px;   
          margin:auto;
      }
      .title{
          position:absolute;
          top:52%;
          left:50%;
          transform: translate(-50%,-50%);
      }
      .title h1{
          
          color:#fff;
          font-size:70px;
          
      }
      .button{
            position:absolute;
          top:59%;
          left:50%;
          transform: translate(-50%,-50%);
      }
      .btn{
          border: 1px solid #fff;
          padding:10px 30px;
          color:#fff;
          text-decoration: none;
          transition: 0.6s ease;
          
      }
      .btn:hover{
            background-color: #fff;
          color:#000;
      }
      
    </style>  
    </head>
    <body>
       <header>
        <div class='main'>
            <div class='logo'>
            <img src='Logo.png'>
            </div>
           <ul>
            <li class='active'><a href='#'>Home</a></li>
            <li><a href='file:///C:/Users/vlogu/Desktop/website%20start%20fr/about.html'>About</a></li>
            <li><a href='file:///C:/Users/vlogu/Desktop/website%20start%20fr/contact.html'>Contact</a></li>
            <li><a href='#'>Gallery</a></li>
              
            </ul>
           </div>
        <div class='title'>
           <h1>OMUL CURIOS</h1>
           </div>
           <div class='button'>
                <a href='https://www.youtube.com/channel/UC_c10z87nB57zoK_Sbih4kQ' target='_blank' class='btn' >YOUTUBE</a>
                <a href='https://www.instagram.com/andrei_baias_/' target='_blank' class='btn'>INSTAGRAM</a>
           </div>
        </header>
   
    </body>

</html>
