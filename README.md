# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            color:burlywood
            font-size: large;
        }
        input:hover{
            background-color:rgb(223, 189, 54);
            color:black;
            font-family: 'Times New Roman';

        }
        input{
            border-radius: 25px;
            width: 500px;
            height: 20px;
            background-color:  rgb(195, 235, 13);
            background-image:url('100.png'),url('111.webp');
            background-position: 1%,98%;
            background-size: 30px;
            background-repeat: no-repeat;
            text-align: center;
            padding: 10px;
            
        }
    </style>
</head>
<body>
    <div style="display: flex;background-color: rgb(237, 252, 170);height: 80px;">
        <div class="row1" style="padding-top: 30px; padding-right: 30px;padding-left: 30px;width: 40%; ">
            <a href="https://twitter.com/"><i class="bi bi-twitter-x" style="padding-right: 7px;"></i></a>
            <a href="https://about.meta.com/"><i class="bi bi-meta" style="padding-right: 7px;"></i></a>
            <a href="https://www.whatsapp.com/"><i class="bi bi-whatsapp" style="padding-right: 7px;"></i></a>
            <a href="https://www.instagram.com/"><i class="bi bi-instagram"  style="padding-right: 7px;"></i></a>
            <a href="https://www.threads.net/login"><i class="bi bi-threads"  style="padding-right: 7px;"></i></a>
        </div>
        <div style="padding-left: 300px; padding-top: 28px; text-decoration: none; font-style: italic;font-weight: 200;width: 40%;">
            <a href="">Alumni</a>
            <i class="bi bi-three-dots-vertical"></i>
            <a href="">Events</a>
            <i class="bi bi-three-dots-vertical"></i>
            <a href="">Cheer</a>
            <i class="bi bi-three-dots-vertical"></i>
            <a href="">Login</a>
            <i class="bi bi-three-dots-vertical"></i>
            <a href="">SEC portal</a>
            <i class="bi bi-three-dots-vertical"></i>
        </div>
        <div style="width: 20%; padding-top: 18px;">
            <input type="text" name="sr" placeholder=" Search " style="width: 200px;" >
        </div>
    </div>

    <div style="display: flex; margin-left: 50px; margin-right: 50px; background-color: chartreuse; height: 120px;">
        <div style="width: 30%; padding-top: 25px;">
            <img src="saveetha logo.png" style="width: 100%;">
        </div>
        <div style="width: 35%;"></div>
        <div style="width: 35%;"></div>
    </div>
    <div>

        <div id="carouselExampleDark" class="carousel carousel-dark slide" style="padding:0% 20px;">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="10000">
                <img src="01.jpeg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="2000">
                <img src="02.jpg" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
              <div class="carousel-item">
                <img src="02.png" class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                </div>
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>

            </button>
          </div>
         

    </div>

    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

</body>
</html>
```
## OUTPUT:
![alt text](output.jpg)

## RESULT:
The program for implementing simple webserver is executed successfully.
