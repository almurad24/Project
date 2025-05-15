......HTML......
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Poppins&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">

    <title>Murad Portfolio</title>
</head>
<body>
   <section class="top-banner flexible-container">
    <div class="half-width">
        <h2 class="text-white">Hello</h2>
        <h1 >
            <span class="text-white"> I am</span> 
            
            Md Al Murad
        </h1>
        <h4>Full Stack web Developer</h4>
        <a class="link" href="#">Let's Talk</a>
    </div>

    <div class="half-width">
        <img src="images/design_photo.png" alt="heroimage">
    </div>
   </section>



   <section class="flexible-container">
       <div class="half-width">
           <img src="images/murad_photo2.png" alt="formalimage">
       </div>
       <div class="half-width">
           <h2>About me</h2>
           <p>Hello, I'm Full Stack web developer from Bangladesh. I create efficient and innovative experience that I user needs and business goal</p>
           <a class="link" href="#">Hire me</a>
       </div>
   </section>


   <section>

        <div class="specialize-head">
            <h2>Specializing In</h2>
            <p>Creating a digital product is full of rewards and challenges. This is why there are certain skills that are crucial if you want to be an effective developer</p>
        </div>


        <div class="parent">
            <div class="child">
                <h3>Frontend web developer</h3>
                <p> Design and maintain digital product and make follow best practice. Also maintain all parts of website like frontend backend design also server.</p>
            </div>
            <div class="child">
                <h3>Backend web developer</h3>
                <p> Design and maintain digital product and make follow best practice. Also maintain all parts of website like frontend backend design also server.</p>
            </div >
            <div class="child">
                <h3>Full Stack web developer</h3>
                <p> Design and maintain digital product and make follow best practice. Also maintain all parts of website like frontend backend design also server.</p>
            </div>
        </div>


   </section>

</body>
</html>



......CSS......

body{
    font-family: 'Poppins', sans-serif;
    margin: 0;
}

h1{
    font-size: 50px;
}

h2{
    font-size: 40px;
}

.text-white{
    color: white;
}

.flexible-container{
    display: flex;
    padding: 5%;
}


.half-width{
    width: 50%;
}
img{
    width: 80%;
    border-radius: 50%;
}

.link{
    text-decoration: none;
    padding: 10px 50px;
    border-radius: 10px;
    background-image: linear-gradient(blue,blueviolet);
    color: white;
    font-weight: 700;
}

.top-banner{

    background-image: url(images/wave.svg);
    background-repeat: no-repeat;
}

.specialize-head{
    text-align: center;
    padding: 0 20% ;
}

.parent{
    display: flex;
    padding: 0 10%;
}

.child{
    box-shadow: 10px 5px 40px black;
    margin: 2%;
    padding: 50px;
    border-radius: 0 20px  50px 0 ;

    border-left: 5px solid;
    border-image: linear-gradient(blue,cyan) 0 100%;
}


footer{
    text-align: center;
}
