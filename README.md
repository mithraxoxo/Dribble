# Project Responsive Web Design using Bootstrap
## Date:02-01-2025

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
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons/font/bootstrap-icons.css" rel="stylesheet">
</head>

<body>

    
    <nav class="navbar navbar-expand-lg navbar-light bg-primary">
        <div class="container">
            <a class="navbar-brand text-white" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link text-white" href="#">Shots</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Teams</a></li>
                    <li class="nav-item"><a class="nav-link text-white" href="#">Jobs</a></li>
                    <li class="nav-item"><a class="btn btn-light btn-sm" href="#">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    
    <div class="bg-dark text-white text-center py-5">
        <h2>What are you working on? Dribbble is show and tell for designers.</h2>
        <div class="mt-3">
            <a href="#" class="btn btn-light btn-sm">Learn More</a>
            <a href="#" class="btn btn-danger btn-sm">Sign Up</a>
        </div>
    </div>

    
    <div class="container py-5">
        <h3 class="mb-4 text-center">Education Icon</h3>
        <div class="row g-4">
            <div class="col-md-3">
                <div class="card">
                    <img src="ramanujam.jpg" class="card-img-top" alt="Design 1">
                    <div class="card-body">
                        <p class="card-text">Ramanujam</p>
                        <p><i class="bi bi-eye"></i> 5,055 | <i class="bi bi-heart"></i> 380</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="A._P._J._Abdul_Kalam.jpg" class="card-img-top" alt="Design 2">
                    <div class="card-body">
                        <p class="card-text">Kalam</p>
                        <p><i class="bi bi-eye"></i> 4,567 | <i class="bi bi-heart"></i> 328</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="newton.jpg" class="card-img-top" alt="Design 3">
                    <div class="card-body">
                        <p class="card-text">Newton</p>
                        <p><i class="bi bi-eye"></i> 4,890 | <i class="bi bi-heart"></i> 679</p>
                    </div>
                </div>
            </div>
            <div class="col-md-3">
                <div class="card">
                    <img src="Albert-Einstein.jpg" class="card-img-top" alt="Design 4">
                    <div class="card-body">
                        <p class="card-text">Albert</p>
                        <p><i class="bi bi-eye"></i> 2,657 | <i class="bi bi-heart"></i> 564</p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    
    <footer class="bg-dark text-white text-center py-4">
        <p class="mb-0">MANIYARASAN R</p>
        <p>
            <a href="#" class="text-white me-3"><i class="bi bi-facebook"></i></a>
            <a href="#" class="text-white me-3"><i class="bi bi-twitter"></i></a>
            <a href="#" class="text-white me-3"><i class="bi bi-instagram"></i></a>
            <a href="#" class="text-white"><i class="bi bi-linkedin"></i></a>
        </p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>

```
## OUTPUT:

![alt text](<Screenshot (17).png>)
![alt text](<Screenshot (18).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
