# Project Responsive Web Design using Bootstrap
## Date:27.12.2024

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#features">Features</a></li>
                    <li class="nav-item"><a class="nav-link" href="#jobs">Jobs</a></li>
                    <li class="nav-item"><a class="nav-link" href="#communities">Communities</a></li>
                    <li class="nav-item"><a class="btn btn-outline-primary me-2" href="#signin">Sign In</a></li>
                    <li class="nav-item"><a class="btn btn-primary" href="#signup">Sign Up</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="bg-primary text-white text-center py-5">
        <div class="container">
            <img src="hero.jpg" alt="Hero Image" class="img-fluid mb-4" style="max-height: 300px;">
            <h1>Unleash Your Creativity</h1>
            <p class="lead">Join a vibrant community where ideas come to life and innovation thrives.</p>
            <a href="#features" class="btn btn-light mt-3">Get Started</a>
        </div>
    </header>

    <section id="features" class="bg-light py-5">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="mb-4">
                        <img src="show case your work.jpg" alt="Showcase" class="img-fluid" style="max-height: 150px;">
                    </div>
                    <h4>Showcase Your Work</h4>
                    <p>Upload and display your best designs to a global audience.</p>
                </div>
                <div class="col-md-4">
                    <div class="mb-4">
                        <img src="collobrate.jpg" alt="Collaborate" class="img-fluid" style="max-height: 150px;">
                    </div>
                    <h4>Collaborate</h4>
                    <p>Connect with like-minded creatives and start new projects together.</p>
                </div>
                <div class="col-md-4">
                    <div class="mb-4">
                        <img src="insipierd.png" alt="Inspiration" class="img-fluid" style="max-height: 150px;">
                    </div>
                    <h4>Get Inspired</h4>
                    <p>Find inspiration from thousands of designs shared by our community.</p>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <div class="container">
            <p class="mb-0">&copy; 2024 Dribbble Clone | Designed by [Ramya G]</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```


## OUTPUT:

![alt text](<Screenshot 2024-12-27 221457.png>)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
