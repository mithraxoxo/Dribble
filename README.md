# Project Responsive Web Design using Bootstrap
## Date: 09.02.2025

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
welcome.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to ClothShop</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">ClothShop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link active" href="sign-in.html">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="shop.html">Shop</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about-us.html">About Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Welcome Section -->
    <section class="jumbotron text-center text-white" style="background: url('cshop.jpg') no-repeat center center; background-size: cover; padding: 100px 0;">
        <div class="container">
            <h1>Welcome to ClothShop</h1>
            <p>Find the latest fashion trends and shop your favorite clothes today!</p>
            <a href="shop.html" class="btn btn-primary btn-lg">Start Shopping</a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 ClothShop. All Rights Reserved.</p>
        </div>
    </footer>
</body>

</html>

```

```
sign-in.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign In - ClothShop</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">ClothShop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="sign-in.html">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="shop.html">Shop</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about-us.html">About Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Sign In Form Section -->
    <section class="container my-5">
        <h2 class="text-center mb-4">Sign In</h2>
        <div class="row">
            <div class="col-md-6 offset-md-3">
                <form>
                    <div class="mb-3">
                        <label for="email" class="form-label">Email address</label>
                        <input type="email" class="form-control" id="email" placeholder="Enter your email">
                    </div>
                    <div class="mb-3">
                        <label for="password" class="form-label">Password</label>
                        <input type="password" class="form-control" id="password" placeholder="Enter your password">
                    </div>
                    <div class="mb-3 form-check">
                        <input type="checkbox" class="form-check-input" id="rememberMe">
                        <label class="form-check-label" for="rememberMe">Remember me</label>
                    </div>
                    <button type="submit" class="btn btn-primary w-100">Sign In</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 ClothShop. All Rights Reserved.</p>
        </div>
    </footer>
</body>

</html>

```

```
shop.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shop - ClothShop</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">ClothShop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="sign-in.html">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="shop.html">Shop</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about-us.html">About Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Shop Section -->
    <section class="container my-5">
        <h2 class="text-center mb-4">Shop Our Collection</h2>
        <div class="row">
            <!-- Product 1 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="jacket.jpg" class="card-img-top" alt="Stylish Jacket">
                    <div class="card-body">
                        <h5 class="card-title">Stylish Jacket</h5>
                        <p class="card-text">A stylish jacket perfect for all seasons.</p>
                        <p class="card-text"><strong>$50.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- Product 2 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="tshirt.jpg" class="card-img-top" alt="Casual T-Shirt">
                    <div class="card-body">
                        <h5 class="card-title">Casual T-Shirt</h5>
                        <p class="card-text">A comfortable t-shirt for daily wear.</p>
                        <p class="card-text"><strong>$25.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- Product 3 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="denim.jpg" class="card-img-top" alt="Denim Jeans">
                    <div class="card-body">
                        <h5 class="card-title">Denim Jeans</h5>
                        <p class="card-text">Classic blue jeans with a perfect fit.</p>
                        <p class="card-text"><strong>$40.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- Product 4 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="snickers.jpg" class="card-img-top" alt="Black Sneakers">
                    <div class="card-body">
                        <h5 class="card-title">Black Sneakers</h5>
                        <p class="card-text">Comfortable sneakers for everyday use.</p>
                        <p class="card-text"><strong>$60.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- Product 5 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="boots.jpg" class="card-img-top" alt="Leather Boots">
                    <div class="card-body">
                        <h5 class="card-title">Leather Boots</h5>
                        <p class="card-text">Stylish leather boots for the winter season.</p>
                        <p class="card-text"><strong>$90.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>

            <!-- Product 6 -->
            <div class="col-md-4 mb-4">
                <div class="card">
                    <img src="sdress.jpg" class="card-img-top" alt="Summer Dress">
                    <div class="card-body">
                        <h5 class="card-title">Summer Dress</h5>
                        <p class="card-text">A beautiful summer dress for warm days.</p>
                        <p class="card-text"><strong>$35.00</strong></p>
                        <a href="#" class="btn btn-primary">Add to Cart</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 ClothShop. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>

```

```
about-us.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - ClothShop</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">ClothShop</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="sign-in.html">Sign In</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link active" href="shop.html">Shop</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="about-us.html">About Us</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Us Section -->
    <section class="container my-5">
        <h2 class="text-center mb-4">About Us</h2>
        <p class="lead text-center">ClothShop is your go-to online store for the latest fashion trends and comfortable
            clothing at affordable prices. We offer a wide variety of products ranging from casual wear to formal attire,
            ensuring that you find something that suits your style.</p>
        <div class="row">
            <div class="col-md-6">
                <h4>Our Vision</h4>
                <p>Our vision is to provide a diverse range of stylish clothing that caters to every occasion and personality.
                    We aim to create a shopping experience that is convenient, affordable, and enjoyable for everyone.</p>
            </div>
            <div class="col-md-6">
                <h4>Our Mission</h4>
                <p>Our mission is to deliver high-quality fashion to our customers, while maintaining a commitment to
                    sustainability and ethical practices. We believe everyone deserves to look good and feel confident.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container text-center">
            <p>&copy; 2024 ClothShop. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2024-12-28 024454.png>)

![alt text](<Screenshot 2024-12-28 024611.png>)

![alt text](<Screenshot 2024-12-28 024512.png>)

![alt text](<Screenshot 2024-12-28 024540.png>)

![alt text](<Screenshot 2024-12-28 024625.png>)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
