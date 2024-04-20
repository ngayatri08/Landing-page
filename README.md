# Landing-page
@import url('https://fonts.googleapis.com/css2?family=Hind&family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,600;1,200&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
header{
    width: 100%;
    height: 100vh;
    background:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)) , url(12.jpg);
    background-size: cover;
    font-family: 'Poppins',sans-serif;
}
nav{
    width: 100%;
    height: 100px;
  
    color: #fff;
    display: flex;
    justify-content: space-around;
align-items: center;
}
.logo{
    font-size: 2em;
    letter-spacing: 2px;
}
.menu a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
}

.menu a:hover{
   border: 1px solid indianred;
   background: transparent;
}
.register a{
    text-decoration: none;
    color: #fff;
    padding: 10px 20px;
    font-size: 20px;
    border-radius: 8px;
    background: indianred;
}
.register a:hover{
    border: 1px solid indianred;
    background: transparent;
}
.h-text{
    position: absolute;
    top: 50%;
    left: 50%;
    max-width: 650px;
    transform: translate(-50%,-50%);
    text-align: center;
    color: #fff;
}
.h-text span{
    letter-spacing: 5px;
}
.h-text h1{
    font-size: 3.5em;
}
.h-text a{
    text-decoration: none;
    background: indianred;
    padding: 10px 20px;
    color: #fff;
    letter-spacing: 5px;
    transition: 0.4s;
}
.h-text a:hover{
    border: 1px solid indianred;
    background: transparent;
}
