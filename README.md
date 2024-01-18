# Mini-project-1
Mini project - Web Design Agency Website


## Description
Here's a mini project I've created using only HTML and CSS. It ia a simple 'Web Design Agency' website.
This mini project focuses on three main CSS properties I've learnt this week:
-CSS Display property
-CSS Float property
-Responsiveness (Media Query)

## Thought Process
Initially, I created a Web Desgin of my project (outcome) in Figma and understood how my elements will be structured.
By doing this, I felt much more easier while coding since I had an idea about how I can make use of different CSS properties.
I also wanted the website to be responsive i.e can be viewed in various screen sizes (which in this case: Desktop and Mobile).

### Desktop View (large screens)

![Desktop view](https://github.com/evarshasharon/mini-project-1/assets/141543660/14bf2986-5018-4815-b7e2-25a679961c12)

### Mobile View (small screens)

![phone view light](https://github.com/evarshasharon/mini-project-1/assets/141543660/20bd3b7e-5bde-4216-ac51-ab889a8e4282)

## HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Design Agency</title>
</head>
<body>
    <div class="logo">
        <h1>dev.com</h1>
    </div>
    <div class="title">
        We are a <span>Creative</span> Design Agency.
    </div>
    <div class="container">
        <div class="card card1">
            <img src="images/1.jpg" alt="">
            <h2>Beauty</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit ipsum, aperiam repellendus recusandae molestias neque minima sapiente consequatur, fugit natus in, iste ad consequuntur error quos?</p>
        </div>
        <div class="card card2">
            <img src="images/2.jpg" alt="">
            <h2>Design</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit ipsum, aperiam repellendus recusandae molestias neque minima sapiente consequatur, fugit natus in, iste ad consequuntur error quos?</p>
        </div>
    </div>
    <footer>
        create. develop. design.
    </footer>
</body>
</html>
```
## CSS
```
.logo{
    color: coral;
    font-style: italic;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 25px;
}

.title{
    font-family: Arial, Helvetica, sans-serif;
    font-weight: bolder;
    font-size: 100px;
    margin: 20px;
    padding-top: 30px;
    
}

.title span{
    color: rgb(16, 66, 34);
}
.title span:hover{
    color: rgb(44, 121, 58);
    
}
@media(max-width:600px){

    .title{
        font-size: 60px;
        margin: 10px;
        padding-top: 15px;
        text-align: center;
        
    }

    .container .card{
        max-width: 100%;
        display: block;
        margin-bottom: 30px;
        text-align: center;

    }
    img{
        margin: 20px;
        display: inline;
        align-items: center;
        object-fit: cover;
    }


}
.container{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    display:inline-block;
    max-width: 100%;
    margin: 40px;
}
.card{
    width: 100%;
    display: inline-block;
    font-size: 22px;
}
.card1{
    max-width: 45%; 
}
img{
    height: 280px;
    width: 280px;
    border-radius: 5px;
    float: left;
    padding-right: 15px;
}
.card2{
    max-width: 45%;
}
footer{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 25px;
    color: blue;
    text-align: right;
    font-weight: bold;
    margin: 25px;
}
```

## Output
### Desktop View
![large screen](https://github.com/evarshasharon/mini-project-1/assets/141543660/9a3ddbae-2b8f-40a8-a5bc-efff15d0f571)

### Mobile View
![small screen](https://github.com/evarshasharon/mini-project-1/assets/141543660/9aed138d-0522-4cb2-a873-6e898ec86eb6)
![small screen1](https://github.com/evarshasharon/mini-project-1/assets/141543660/f52a910e-49ea-491d-85b2-3492f33ec357)

