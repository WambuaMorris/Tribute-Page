# Tribute-Page
This was my first web development project. I guess we've all come from nowhere.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute Page</title>
    <h1><strong>Free Code Camp Tribute Page</strong>></h1>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    
   <main> <div >
        <img src="https://images.unsplash.com/photo-1648737966614-55e58b5e3caf?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxlZGl0b3JpYWwtZmVlZHwyMXx8fGVufDB8fHx8&auto=format&fit=crop&w=500&q=60" alt="" id = "img-div" >
        <hr>
        <section id = "main-part">
        <h2 ><u>Tribute</u></h2>
        <p id="tribute-info"> Lorem ipsum dolor, sit amet consectetur adipisicing elit.
             Sapiente eius molestiae libero, a, exercitationem, similique voluptatem
              dolor dolorum architecto facere blanditiis nam laudantium odio 
              quod rerum laborum unde asperiores magni.Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              Sapiente eius molestiae libero, a, exercitationem, similique voluptatem
               dolor dolorum architecto facere blanditiis nam laudantium odio 
               quod rerum laborum unde asperiores magni.

            <a href="www.freecodecamp.org" target="_blank"> Check it out here.</a>
        </p>

    </div>
</main>
</section>
</body>
</html>

--------CSS------\
#img-div{
    max-width: 100%;
    height: auto;
    
    margin-left: 420px;
    border-style: solid;
    border-width: 3px;
    border-color: aqua;
    border-radius: 10%;
}
h1{
    font-family: monospace;
    position: relative;
    text-align: center;
    color: #092382;
    font-size: 200%;
    font-weight: 1000%;
    
    
}
h2{
    font-family: monospace;
    position: relative;
    margin: 30px;
    text-align: center;
    color: aliceblue;
    font-weight: 700%;
}
p {
    font-family: monospace;
    position: relative;
    margin: 50px;
    text-align: center;
    border-style: solid;
    border-width:4px;
    border-radius: 10px;
    border-color:black;
    font-size: 150%;
    color: aliceblue;

}
#main-part{
    background-color: black;
    border-radius: 10px;
}
a:hover{
    color: chartreuse;
}
