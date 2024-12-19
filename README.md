# Project Responsive Web Design using Bootstrap
## Date:19/12/24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
index.html

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dribble.io</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link href="style.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
        <div class="container">

       <a 
       href="#Logo"
       
       class="navbar-brand mb-0 h1" >
        <img src="logo2.png" width="120" height="30">
    
    </a>
   
    <div class="collapse navbar-collapse"
    id="navbarNav">
    <ul class="navbar-nav">
        <li class="nav-item active">
            <a href="#" class="nav-link active">
                Shots
            </a>
        </li>
        <li class="nav-item active">
            <a href="#" class="nav-link active">
                Designer
            </a>
        </li>
        <li class="nav-item active">
            <a href="#" class="nav-link active">
                Sign up
            </a>
        </li>
        <li class="nav-item active">
            <a href="#" class="nav-link active">
                Sign in
            </a>
        </li>
        
    </ul>
    <div class="ms-auto">
        <form class="d-flex" role="search">
            <input class="form-control me-2" type="text" placeholder="Search" aria-label="Search">
            <button class="btn btn-primary" type="submit">Search</button>
        </form>
    </div>   
    </div>

    </div>
    </nav>

    <section class="text-center py-4" style="background: linear-gradient(to right, #4b4b4b, #7d7d7d);">
        <div class="container">
            <p class="lead fw-bold text-white" style="font-size: 1rem;">What are you working on? Dribbble is show and tell for designers.</p>
            <div class="d-inline-flex gap-2">
                <a href="#" class="btn btn-primary">Learn More</a>
                <a href="#" class="btn btn-outline-brand">Sign Up</a>
            </div>
            
        </div>
    </section>
    <div class="cards-wrapper">
    <div class="card" style="width: 18rem;">
        <img src="img1.jpg" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Joshua</h5>
          <a href="#" class="btn btn-primary - btn-sm">View</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="img2.jpg" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Anderson</h5>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="img3.jpg" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Style Designer</h5>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="img 4.jpg" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Mathew</h5>
          <p class="card-text"></p>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
        
      </div>
      <div class="card" style="width: 18rem;">
        <img src="jslash.jpg" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">jslash</h5>
          <p class="card-text"></p>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
        
      </div> <div class="card" style="width: 18rem;">
        <img src="ulquro.avif" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Ulquira</h5>
          <p class="card-text"></p>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
        
      </div> <div class="card" style="width: 18rem;">
        <img src="YHwach.avif" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Graciala</h5>
          <p class="card-text"></p>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
        
      </div> <div class="card" style="width: 18rem;">
        <img src="Aaron.avif" class="card-img-top" alt="">
        <div class="card-body">
          <h5 class="card-title">Hans zimmer</h5>
          <p class="card-text"></p>
          <a href="#" class="btn btn-primary btn-sm">View</a>
        </div>
        
      </div>
      </div>


   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
  </body>
  <footer id="footer">
    <h2 style="background-color: dimgray; text-align: center;font-size: 18px;">Designed and developed by K Barathaj(24001402)</h2>
</footer>
</html>

style.css

.btn-outline-brand {
    background-color: deeppink;
}
.cards-wrapper {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1em;
}
.card{
    margin: 0.5em;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    transition: transform 0.3s ease;
    }
.card-img-top{
    width: 100%;
    height: 100%;
    object-fit: cover;

}

.footer {
    font-size: 12px;
    text-align: center;
    padding: 1em 0;
    background-color: dimgray;
    color: white;
}
.card-title {
    font-size: 1.25rem;
    font-weight: bold; 
    color: #343a40; 
    text-align: center; 
    margin-bottom: 0.5rem; 
    transition: color 0.3s ease; 
}



```

## OUTPUT:
![alt text](image.png)
![alt text](image-1.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
