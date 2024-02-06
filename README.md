## Landing page
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>landing page</title>
    <link rel="stylesheet" type="text/css" href="css/page.css">


</head>
<body>
    <header class="head">
        <h1 align="center">SANS HOTELS</h1>
    </header>  
    <div class="homeimage">
        <img src="css/images/pexels-pixabay-258154.jpg" width="900" height="500">
    </div>
    <section>
        <div class="about">
            <a href="#">Our hotels</a>
            <a href="#">offers</a>
            <a href="#">sustainablity</a>
            <a href="#">Mobile app</a>
            <a href="#">Gift Card</a>
            <a href="#">Login</a>
        </div> 
    </section>    
    <section class="picture">
        <h1>ABOUT US</h1>
        <h3>Spend Your Leisure time</h3>
        <p>Discover comfort and hospitality at its finest with SANS Hotels. Centrally located in OMR,Chennai, we offer a seamless blend of modern luxury and personalized service.
         At SANS Hotels, our mission is simple: to make your stay unforgettable. From our thoughtfully designed rooms to our attentive staff, every detail is crafted to ensure your comfort and satisfaction.Our team is dedicated to providing exceptional service from check-in to check-out. Let us take care of the details, so you can focus on making the most of your time in OMR,Chennai
            We invite you to experience SANS Hotel's unique charm. Book your stay with us and discover a place where hospitality meets comfort. We look forward to welcoming you soon!</p>

        <div class="image">
        <img src="css/images/room.jpg">
    </div>
    </section>    
    
</body>
</html>
```
## css
```
body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: whitesmoke;
}

.head {
    background-color: antiquewhite;
    padding: 4px;
}

.homeimage {
    width: 100%;
    display:block;
}

.about {
    display: inline-block;
    position: absolute;
    top: 13px;
    right: 0;
    padding: 10px 20px;
    background-color: antiquewhite;
    color: whitesmoke;
    font-size: 20px;
    cursor: pointer;
    border: none;
    border-radius: 0px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    font-weight: bolder;
    word-spacing: 6px;
}

.about:hover {
    background-color: antiquewhite;
}

* {
    box-sizing: border-box;
}

.picture {
    overflow: hidden;
}

.picture p {
    float: left;
    width: 40%;
    margin:0;
    padding: 20px;
    height: 400px;
    font-style: italic;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.picture img {
    float: right;
    width: 60%;
    max-height: 400px;
}
.side-img{
    float:left;
    width:60%
}
.image{
    float: right;
    margin-right: 10px;
}
```
