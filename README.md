<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title align:"center">Minha Loja Online</title>
    <style>
                * {
                    margin: 0;
                    padding: 0;
                }

                .main {
                    width: 100%;
                    background: linear-gradient(to top, rgba(0,0,0,0.5) 50%, rgba(0,0,0,0.5) 50%), url('https://audaces.com/wp-content/uploads/2022/10/women-s-fashion-store-shopping-center-1024x683.jpg');
                    background-position: center;
                    background-size: cover;
                    height: 100vh;
                }
                
                .navbar {
                    width: 1200px;
                    height: 75px;
                    margin: auto;
                }
                
                .icon {
                    width: 200px;
                    float: left;
                    height: 70px;
                }
                
                .logo {
                    color: #728fc6;
                    font-size: 35px;
                    font-family: Arial;
                    padding-left: 20px;
                    float: left;
                    padding-top: 10px;
                    margin-top: 5px;
                }
                
                .menu {
                    width: 400px;
                    float: left;
                    height: 70px;
                }
                
                ul {
                    float: left;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                }
                
                ul li {
                    list-style: none;
                    margin-left: 62px;
                    margin-top: 27px;
                    font-size: 14px;
                }
                
                ul li a {
                    text-decoration: none;
                    color: #fff;
                    font-family: Arial;
                    font-weight: bold;
                    transition: 0.4s ease-in-out;
                }
                
                ul li a:hover {
                    color: #004cff;
                }
                
                .search {
                    width: 330px;
                    float: left;
                    margin-left: 270px;
                }
                
                .srch {
                    font-family: 'Times New Roman';
                    width: 200px;
                    height: 40px;
                    background: transparent;
                    border: 1px solid #0d00ff;
                    margin-top: 13px;
                    color: #fff;
                    border-right: none;
                    font-size: 16px;
                    float: left;
                    padding: 10px;
                    border-bottom-left-radius: 5px;
                    border-top-left-radius: 5px;
                }
                
                .btn {
                    width: 100px;
                    height: 40px;
                    background: #0000ff;
                    border: 2px solid #0011ff;
                    margin-top: 13px;
                    color: #fff;
                    font-size: 15px;
                    border-bottom-right-radius: 5px;
                    border-bottom-right-radius: 5px;
                    transition: 0.2s ease;
                    cursor: pointer;
                }
                
                .btn:hover {
                    color: #000;
                }
                
                .btn:focus {
                    outline: none;
                }
                
                .srch:focus {
                    outline: none;
                }
                
                .content {
                    width: 1200px;
                    height: auto;
                    margin: auto;
                    color: #fff;
                    position: relative;
                }
                
                .content .par {
                    padding-left: 20px;
                    padding-bottom: 25px;
                    font-family: Arial;
                    letter-spacing: 1.2px;
                    line-height: 30px;
                }
                
                .content h1 {
                    font-family: 'Times New Roman';
                    font-size: 50px;
                    padding-left: 20px;
                    margin-top: 9%;
                    letter-spacing: 2px;
                }
                
                .content .cn {
                    width: 160px;
                    height: 40px;
                    background: #001eff;
                    border: none;
                    margin-bottom: 10px;
                    margin-left: 20px;
                    font-size: 18px;
                    border-radius: 10px;
                    cursor: pointer;
                    transition: .4s ease;
                }
                
                .content .cn a {
                    text-decoration: none;
                    color: #000;
                    transition: .3s ease;
                }
                
                .cn:hover {
                    background-color: #fff;
                }
                
                .content span {
                    color: #000dff;
                    font-size: 65px;
                }
                
                .form {
                    width: 250px;
                    height: 380px;
                    background: linear-gradient(to top, rgba(0,0,0,0.8) 50%, rgba(0,0,0,0.8) 50%);
                    position: absolute;
                    top: -20px;
                    left: 870px;
                    transform: translate(0%,-5%);
                    border-radius: 10px;
                    padding: 25px;
                }
                
                .form h2 {
                    width: 220px;
                    font-family: sans-serif;
                    text-align: center;
                    color: #0d00ff;
                    font-size: 22px;
                    background-color: #fff;
                    border-radius: 10px;
                    margin: 2px;
                    padding: 8px;
                }
                
                .form input {
                    width: 240px;
                    height: 35px;
                    background: transparent;
                    border-bottom: 1px solid #0004ff;
                    border-top: none;
                    border-right: none;
                    border-left: none;
                    color: #fff;
                    font-size: 15px;
                    letter-spacing: 1px;
                    margin-top: 30px;
                    font-family: sans-serif;
                }
                
                .form input:focus {
                    outline: none;
                }
                
                ::placeholder {
                    color: #fff;
                    font-family: Arial;
                }
                
                .btnn {
                    width: 240px;
                    height: 40px;
                    background: #003cff;
                    border: none;
                    margin-top: 30px;
                    font-size: 18px;
                    border-radius: 10px;
                    cursor: pointer;
                    color: #fff;
                    transition: 0.4s ease;
                }
                
                .btnn:hover {
                    background: #fff;
                    color: #1e00ff;
                }
                
                .btnn a {
                    text-decoration: none;
                    color: #000;
                    font-weight: bold;
                }
                
                .form .link {
                    font-family: Arial, Helvetica, sans-serif;
                    font-size: 17px;
                    padding-top: 20px;
                    text-align: center;
                }
                
                .form .link a {
                    text-decoration: none;
                    color: #2600ff;
                }
                
                .liw {
                    padding-top: 15px;
                    padding-bottom: 10px;
                    text-align: center;
                }
                
                .icons a {
                    text-decoration: none;
                    color: #fff;
                }
                
                .icons ion-icon {
                    color: #fff;
                    font-size: 30px;
                    padding-left: 14px;
                    padding-top: 5px;
                    transition: 0.3s ease;
                }
                
                .icons ion-icon:hover {
                    color: #0d00ff;
                }
            </style>
</head>
<body>
    <div class="main">
        <div class="navbar">
            <div class="icon">
                <h2 class="logo">PraRoz</h2>
            </div>
    <header>
        <div class="logo">
            <h1><a href="#">Minha Loja</a></h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="produto.html">Produtos</a></li>
                <li><a href="#">Sobre Nós</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
        <div class="search">
            <input class="srch" type="search" name="" placeholder="Type To text">
            <a href="#"> <button class="btn">Search</button></a>
        </div>
        <div class="cart">
            <a href="#">Carrinho</a>
        </div>
    </header>

    <main>
            <div class="content">
                <h1>Web Design & <br><span>Development</span> <br>Course</h1>
                <p class="par">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt neque 
                     expedita atque eveniet <br> quis nesciunt. Quos nulla vero consequuntur, fugit nemo ad delectus 
                    <br> a quae totam ipsa illum minus laudantium?</p>
    
                    <button class="cn"><a href="#">JOIN US</a></button>/
                    <div class="form">
                        <form action="flask.py" method="post">
                            <h2>LOGIN</h2>

                            <input type="text" name="nome" placeholder="Enter Nome Here">
                            <input type="email" name="email" placeholder="Enter Email Here">
                            <input type="text" name="cep" placeholder="Enter CEP Here">
                            <button type="submit" class="btnn">Login</button>
                    
                            <p class="link">Don't have an account?<br>
                            <a href="#">Sign up here</a></p>
                    
                            <p class="liw">Log in with</p>
                        </form>
                        <div class="icons">
                            <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                            <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                            <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                        </div>
        </section>
    </main>

    <footer>
        <h2>Contato:</h2>
        <div class="icons">
            <a href=""><ion-icon name="logo-facebook"></ion-icon></a>
            <a href="https://www.instagram.com/gucci/"><ion-icon name="logo-instagram"></ion-icon></a>
            <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
        </div>    
        <p>&copy; 2023 Minha Loja Online. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
