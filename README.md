# haider
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.0/css/all.min.css">
    <link rel="stylesheet" href="./stayles.css">
    <title>Haider-M</title>
</head>
<body>
    <header>
        <a href="#" class="logo">Haider-M</a>
        <nav class="navig">
            <a href="#services">services</a>
            <a href="#projects">projects</a>
            <a href="#contact">contact</a>

        </nav>
    </header>

    <section class="main">
        <div>
            <h2>Hello,I'm Haider <br><span>Website designer, app developer</span></h2>
            <h3>Work on web design and LEGO</h3>
            <a href="#projects" class="main-btn">my work</a>
            <div class="social-icons">
                <a href="#"><i class="fa-brands fa-github"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
                <a href="#"><i class="fa-brands fa-youtube"></i></a>
                <a href="#"><i class="fa-brands fa-telegram"></i></a>
            </div>
        </div>

    </section>

    <section class="cards" id="services">
        <h2 class="title">Services</h2>
        <div class="content"> 
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-pen-to-square"></i>
                </div>
                <div class="info">
                    <h3>writing</h3>
                    <p>Research and writi for different topics that can then be directly recorded for video praduction</p>
                </div>
            </div>
        </div>
        <div class="content"> 
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-pen-to-square"></i>
                </div>
                <div class="info">
                    <h3>writing</h3>
                    <p>Research and writi for different topics that can then be directly recorded for video praduction</p>
                </div>
            </div>
        </div>
        <div class="content"> 
            <div class="card">
                <div class="icon">
                    <i class="fa-solid fa-pen-to-square"></i>
                </div>
                <div class="info">
                    <h3>writing</h3>
                    <p>Research and writi for different topics that can then be directly recorded for video praduction</p>
                </div>
            </div>
        </div>
    </section>

</body>
</html>




***********************************CSS********************************************************************

@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,600&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
*{
   
font-family: 'Poppins', 'sans-serif';
margin: 0;
padding: 0;
box-sizing: border-box;
scroll-behavior: smooth;
}
/* *************************************
****************haeder******************* */
header{
    background-color: antiquewhite;
    width: 100%;
    position: fixed;
    z-index: 999;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 200px ;
}

.logo{
    text-decoration: none;
    color: royalblue;
    text-transform: uppercase;
    font-weight: 700;
    font-size: 1.8em;
}

.navig a {
    color: royalblue;
    text-decoration: none;
    font-weight: 500;
    font-size: 1.1em;
    padding-left: 30px;
    transition: 0.4s ease;
}

.navig a:hover{
    color:black;
}

section{
    padding: 100px 200px ;
}

.main{
    width: 100%;
    min-height: 100vh;
    display: flex;
    align-items: center;
    background-color:beige;
    background: url(./imeges/stock-photography-happiness-happy-man-image-royalty-free-man-3edcc67d5a53a7c950c28eec07947f1d.png) no-repeat;
    background-size: 400px;
    background-position: right;
    background-attachment: fixed;
}

.main h2 {
    color: rgb(63, 57, 57);
    font-size: 1.4em;
    font-weight: 600;
    letter-spacing: 1px;
}

.main h2 span {
    display: inline-block;
    margin-top: 10px;
    color: blue;
    font-size:2em ;
    font-weight: 500;
}

.main h3 {
    color: rgb(63, 57, 57) ;
    font-size: 1.6em;
    font-weight: 500;
    letter-spacing: 1px;
    margin-top: 10px;
    margin-bottom: 3px;
}

.main-btn {
    color: antiquewhite;
    background-color: coral;
    text-decoration: none;
    font-size: 1em;
    font-weight: 600;
    display: inline-block;
    padding: 0.9375em 2.1875em;
    letter-spacing: 1px;
    border-radius: 15px;
    margin-bottom: 40px;
    margin-top: 20px;
    transition: 0.3s ease;
}

.main-btn:hover {
    background-color: rgb(253, 97, 40);
    transform: scale(1.1);
}

.social-icons a {
    color: black;
    font-size: 1.6em;
    padding-right: 30px;
}

.title {
    display: flex;
    justify-content: center;
    color:royalblue ;
    font-size: 2.2em;
    font-weight: 700;
    margin-bottom: 30px;
}

.content {
    display: flex;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap ;
}

.card {
    background-color:beige;
    width: 21.25em;
    box-shadow: 0 5px 25px rgba(1 1 1 / 15%);
    border-radius: 10px;
    padding: 25px;
    margin: 15px;
}
