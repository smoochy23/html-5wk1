# html-5wk1

*{
    margin: 0;
    padding: 0;
    background-position: center;

}
body
{
    background-image:url(../../Pictures/james.img1.png) ;
    background-size: cover;
    box-sizing: border-box;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.navba{
    width: 100%;
    height:80px;
    padding-top: 10px ;
    background-color: black;
}

.navg{
    display: flex;
    color: white;
    text-decoration: none;
    list-style: none;
    flex-direction: row;
}
.nav-item{
font-size: 25px;
margin:45px ;
background-color: black;
}
.nav-item a:hover
{
    background-color: rgb(22, 19, 19);
    border-radius: 3px;
}
.image-container{
    position: relative;
    width: 800px;
    max-height: 365px;


}
.navbar{
    width: 200px;
    background-color: black;
    text-decoration: none;
    margin: 10px;
    padding: 10px;
}
.nav{
    display: block;
    color: white;
    text-decoration: none;
    list-style: none;
    flex-direction: column;
}

.main-content {
    width: 1000px;
    margin-left: 240px;
    position: fixed;
    top: 0;
    margin-top: 100px;
}
#verticle-line{
    width: 200px;
    height: auto;
    background-color: blue;

}
.cards{
    margin: 0;
    flex-direction: row;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>navigation</title>
    <link rel="stylesheet"href="ALFA.css">
</head>
<body>

    <div class="navba">
        <ol class="navg">
            <li  class="nav-item">Home</li>
            <li  class="nav-item">Project</li>
            <li  class="nav-item">Services</li>
            <li  class="nav-item">Booking</li>

        </ol>
    </div>

    <div class="navbar">
        <ul class="nav">
            <li class="nav-item"><a href="#">Home</a></li>
            <li class="nav-item"><a href="#">Project</a></li>
            <li class="nav-item"><a href="#">Services</a></li>
            <li class="nav-item"><a href="#">Booking</a></li>
        </ul>
    </div>
    <div class="main-content">
        <div class="image-container">
            <img src="img1.png" alt="profile image" class="image-container">
        </div>
    </div>
    <div class="verticle-line">
        <div id="verticle-line"></div>
    </div>
    <div>
        <div class="cards">
            <section id="card">
                <div class="car">
                    <p>Welcom</p>
                </div>
                <div class="car">
                    <p>invites</p>
                </div>
                <div class="car">
                    <p>Enquiries</p>
                </div>
                <div class="car">
                    <p>Q&A</p>
                </div>
            </section>
        </div>
    </div>

</body>
</html>
