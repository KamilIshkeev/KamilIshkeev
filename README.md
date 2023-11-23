<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Robotics</title>
    <link rel="stylesheet" href="CSS/style.CSS">
    <link rel="shortcut icon" href="img/favicon.png" type="image/x-icon">
</head>
<body>
    <header>
        <div class="container section">
        <div class="logo">
            <img src="img/logo.png" alt="">
            <H2>Robotics</H2>
        </div>
        
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Products</a>
        </nav>
        </div>
    </header>

    <main>
        <div class="banner section">
            <h1>Products</h1>
            <div class="link">
                <a href="#">Home</a>→<a href="#">Products</a>
                
                
            </div>
        </div>
    </main>

    <div class="cards section">
        <div class="title">
            <h2>Lorem ipsum dolor sit amet.</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui, magnam?</p>
        </div>

        <div class="card-items">

            <div class="item">
                <img src="img/p1.png" alt="">
                <div class="item-text">
                    <h3>The Upper Eye</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, error.</p>
                </div>
                <div class="item-button">
                    <a href="">View Details</a>
                </div>
            </div>

            <div class="item">
                <img src="img/p1.png" alt="">
                <div class="item-text">
                    <h3>The Upper Eye</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, error.</p>
                </div>
                <div class="item-button">
                    <a href="">View Details</a>
                </div>
            </div>
            <div class="item">
                <img src="img/p1.png" alt="">
                <div class="item-text">
                    <h3>The Upper Eye</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis, error.</p>
                </div>
                <div class="item-button">
                    <a href="">View Details</a>
                </div>
            </div>

        </div>
    </div>

    <footer>
        <div class="footer-main section">
            <div class="footer-form">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, debitis!</p>
                <div class="footer-input">
                    <input type="text" placeholder="email@mail.ru">
                    <button>Подписаться</button>
                </div>
            </div>

            <div class="footer-img">
                <img src="img/vk.png" alt="">
                <img src="img/youtube.png" alt="">
            </div>
        </div>
    </footer>

</body>
</html>








* {
    margin: 0;
    padding: 0;
    text-decoration: none;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    transition: 0.5s;
}

header {
    width: 100%;
    
    background: #525e8fe8;
}

.container {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: white;
    padding: 20px 0;
}

.section {
    max-width: 1200px;
    margin: 0 auto;
}
.logo{
    display: flex;
    gap: 40px;
    align-items: center;
}

nav {
    display: flex;
    gap: 100px; 
}

nav a {
    color: white;
    text-transform: uppercase;
    font-weight: bold;

}

nav a:hover {
    color: red;
}

main {
    width: 100%;
    background-image: url(../img/banner-bg.jpg);
    background-size: cover;
    height: 300px;
    background-position: center;
}

.banner {
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.banner h1 {
    color: white;
    font-size: 50px;
}

.banner .link {
    display: flex;
    gap: 20px;
    color: white;
    align-items: center;
}

.banner .link a {
   color: white;
   font-size: 15px;
   text-transform: uppercase;
   font-weight: bold;
}

.cards .title {
    text-align: center;
    padding: 60px 0;
    line-height: 30px;
}

.card-items {
    display: flex;
    justify-content: space-between;
    padding-bottom: 50px;
}

.item {
    width: 25%;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    box-shadow: 0 2px 7px #9e90ff;
    padding: 20px;
    border-radius: 15PX;
}

.item img{
    width: 30%;
}

.item-text h3{
    padding: 10px 0;
}

.item-button{
    width: 100%;
    padding: 10px 0;
} 

.item-button a{
    background: #151c39e8;
    color: white;
    display: block;
    padding: 10px 80px;
    box-shadow: 0 2px 7px #9e90ff;
    border-radius: 15px;
}

footer {
    background: url(../img/footer-bg.jpg);
    background-size: cover;
    color: white;
    padding: 80px 0;

}

.footer-main{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer-form {
    width: 30%;
}

.footer-input input{
    padding: 7px;
    border-radius: 10px;
    margin-top: 10px;
    outline: none;
}

.footer-input button {
    padding: 7px;
    border-radius: 10px;
    text-transform: uppercase;
}

.footer-img {
    display: flex;
    gap: 60px;
}

.footer-img img{
    width: 80px;
}

.footer-img img:hover{
    transform: rotate(360deg);
}
