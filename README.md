# Project Responsive Web Design using Bootstrap
## Date:08/05/2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
app.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=20">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">JK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-10 mb-10">
    <div class="container">
      <h1>EASY ACCESS TO HEALTHCARE</h1>
      <p class="lead">Our aim is to provide healthcare and medicines to people in remote areas.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFO</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="m1.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">We are prone to update our machines to more enhanced way to make sure of your health needs</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="m2.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Our commitment to quality ensures the safety and cleanliness of rooms to avoid spreading od disease.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="m3.jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text">We are so kind to our patient.Its our responsibility to take a complete care of them.Every patient is equal to us no matter they are rich or poor.We respect our patients.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 JK Pharma KEERTHANA S (212223040092) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>

```
```
products.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">JK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-50">
    <h1 class="text-center mb-50">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-5 row-cols-lg-3 g-3">
      <div class="col mb">
        <div class="card">
          <img src="m4.jpg" class="card-img-top mb-50" alt="Product Image">
          <div class="card-body mb-20">
            <h5 class="card-title">Follihair</h5>
            <p class="card-text">Follihair Tablet is a specialised medicine aimed at promoting the growth of healthy hair. This tablet serves as a valuable multivitamin supplement, bringing together a blend of important nutrients such as biotin, amino acids, vitamins, minerals, and natural extracts.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col-md-3">
        <div class="card">
          <img src=" m5.png" class="card-img-top mb-50" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> Biotin</h5>
            <p class="card-text mb-20">Follihair Tablet is a specialised medicine aimed at promoting the growth of healthy hair. This tablet serves as a valuable multivitamin supplement, bringing together a blend of important nutrients such as biotin, amino acids, vitamins, minerals, and natural extracts.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="m6.jpeg" class="card-img-top mb-50" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Vitamin C</h5>
            <p class="card-text mb-20"> Vitamin C is needed for the body to develop and function properly. It plays an important role in immune function. Most experts recommend getting vitamin C from the diet rather than taking supplements. Fresh oranges and fresh-squeezed orange juice are good sources.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer class="text-center py-10 bg-light">
    <p>&copy; 2024 JK Pharma KEERTHANA S (212223040092) </p>
  </footer>

</body>
</html>

```

```
event.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Events</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">JK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-10">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="m7.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Microbial Warfare in the Gut: Probiotics vs. Dysbiosis</h5>
            <p class="card-text">Probiotics are beneficial bacteria that promote gut health, combating dysbiosis—an imbalance in the gut microbiota linked to various digestive disorders and immune dysfunctions. This microbial warfare within the gut ecosystem highlights the importance of maintaining a healthy balance of gut flora for overall well-being.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="m8.png" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Gene Editing Battles Genetic Disorders: CRISPR vs. Inherited Diseases</h5>
            <p class="card-text">Gene editing technologies like CRISPR offer the potential to correct genetic mutations responsible for inherited diseases. This interior medical war involves precise manipulation of DNA sequences to combat conditions ranging from cystic fibrosis to sickle cell anemia, ushering in a new era of personalized medicine.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 JK Pharma KEERTHANA S (212223040092) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```

```
about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">JK Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="event.html">Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="about.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>JK Pharma</p>
        <p>JK Pharma
           shanthi nagar,
           Kalyan residency road,
           Bangaluru 560043.
        </p>
        <p>Phone Number: <a href="tel:+1234567890">256-562-9547</a></p>
        <p>Email: <a href="mailto:info@yourcompany.com">info@JK.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 JK Pharma KEERTHANA S (212223040092) </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>


```
## OUTPUT:
![alt text](<Screenshot 2024-05-08 225431.png>)
![alt text](<Screenshot 2024-05-08 225514.png>)
![alt text](<Screenshot 2024-05-08 225530.png>)
![alt text](<Screenshot 2024-05-08 225559.png>)



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
