# Project Responsive Web Design using Bootstrap
## Date:

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
### Register num :212223230122
### Name :MANOJ M
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmagenix</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <style>
    body nav {
      font-family:Verdana, Geneva, Tahoma, sans-serif
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Pharmagenix</a>
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
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="news&events.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>Transforming Healthcare with Innovation</h1>
      <p class="lead">At Pharmagenix, we are committed to developing groundbreaking medications and technologies for a healthier future.</p>
      <a href="#" class="btn btn-outline-primary btn-lg">Discover More</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="cdv.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Cutting-Edge Research & Development</h5>
            <p class="card-text">Pharmagenix invests significantly in research and development to discover and develop innovative medications and medical technologies.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="quality.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Quality Assurance</h5>
            <p class="card-text">The company maintains rigorous quality control measures throughout the manufacturing process to ensure the safety, efficacy, and consistency of its products.</p>
         </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="care.jpg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient-Centered Approach</h5>
            <p class="card-text">Pharmagenix prioritizes patient care and safety, offering comprehensive support services and educational resources to enhance treatment outcomes and improve the overall quality of life for patients.</p>
        </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
### products.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmagenix</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <style>
    body h5 p nav {
      font-family:Verdana, Geneva, Tahoma, sans-serif;
    }
    .card-body {
      height: 100%;
    }
    .card-img-top {
      object-fit: cover;
      height: 200px; /* Adjust the height as needed */
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Pharmagenix</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="homepage.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="news&events.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>Transforming Healthcare with Innovation</h1>
      <p class="lead">At Pharmagenix, we are committed to developing groundbreaking medications and technologies for a healthier future.</p>
      <a href="#" class="btn btn-outline-primary btn-lg">Discover More</a>
    </div>
  </section>

  <section class="container">
    <div class="row justify-content-center">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="product1.jpg" class="card-img-top" alt="Product 1">
          <div class="card-body">
            <h2 class="card-title">Painrelief+</h2>
            <p class="card-text">PainRelief+ is a revolutionary pain management medication developed by Pharmagenix to provide fast and effective relief from acute and chronic pain. This advanced formula combines potent analgesic agents with innovative delivery.
            </p>
            <a href="#" class="btn btn-primary">View Details</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="product2.jpg" class="card-img-top" alt="Product 2">
          <div class="card-body">
            <h2 class="card-title">ImmunoBoost Capsules</h2>
            <p class="card-text">ImmunoBoost Capsules are a potent immune system support supplement designed to enhance the body's natural defense mechanisms against infections and illnesses. Formulated with a blend of vitamins, minerals, and herbal extracts, these capsules provide comprehensive immune support to help you stay healthy and resilient year-round.
            </p>
            <a href="#" class="btn btn-primary">View Details</a>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="product3.jpg" class="card-img-top" alt="Product 3">
          <div class="card-body">
            <h2 class="card-title">NeuroCalm Drops</h2>
            <p class="card-text">NeuroCalm Drops are a natural remedy for stress and anxiety, formulated to promote relaxation, improve mood, and support mental well-being. This unique blend of botanical extracts and calming nutrients helps to soothe frazzled nerves, reduce tension, 
                and restore emotional balance, allowing you to face life's challenges with calm and confidence.</p>
            <a href="#" class="btn btn-primary">View Details</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
### News & Events
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharmagenix</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <style>
    body h2 nav {
      font-family:Verdana, Geneva, Tahoma, sans-serif
    }

  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Pharmagenix</a>
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
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="news&events.html">News & Events</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container mt-5">
    <h2 class="text-center mb-4">Latest News & Events</h2>
    <div class="row">
      <div class="col-md-6">
        <div class="card mb-4">
          <img src="event1.webp" class="card-img-top" alt="Event Image 1">
          <div class="card-body">
            <h2 class="card-title">Breakthrough in Cancer Treatment:</h2>
            <p class="card-text">Pharmagenix announces a groundbreaking advancement in cancer therapy with the successful completion of Phase III clinical trials for a novel immunotherapy drug. This innovative treatment shows promising results in improving overall survival rates and reducing adverse effects in patients with advanced-stage cancer.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <div class="card mb-4">
          <img src="event2.svg" class="card-img-top" alt="Event Image 2">
          <div class="card-body">
            <h5 class="card-title">Clinical Trial Symposium: Investigational Drug Trial Results</h5>
            <ul>
                <li>Date: April 5, 2024</li>
                <li>Time: 9:00 Am - 3:00 PM </li>
                <li>Description:</li>
            </ul>
            <p class="card-text"></p>
                Pharmagenix is hosting a symposium to present the results of our latest investigational drug trials. Researchers will share findings from clinical trials evaluating the safety and efficacy of potential new therapies for various medical conditions, including cardiovascular disease, autoimmune disorders, and neurodegenerative diseases. This event is open to healthcare professionals, researchers, and industry stakeholders interested in the latest developments in drug discovery and development.</p>
            <a href="#" class="btn btn-primary">Read More</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
     </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
```
### contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Pharmagenix</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <style>
    body nav {
      font-family:Verdana, Geneva, Tahoma, sans-serif
    }
  </style>
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Pharmagenix</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="homepage.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">Our Story</a></li>
              <li><a class="dropdown-item" href="#">Our Mission</a></li>
              <li><a class="dropdown-item" href="#">Leadership Team</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="news&events.html">News & Events</a>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container mt-5">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="row justify-content-center">
      <div class="col-md-6">
        <p>Feel free to reach out to us through the following contact methods:</p>
        <ul class="list-unstyled">
          <li><strong>Phone:</strong> +1 (123) 456-7890</li>
          <li><strong>Email:</strong> info@pharmagenix.com</li>
        </ul>
        <p>Our office hours are Monday to Friday, 9:00 AM to 5:00 PM.</p>
      </div>
    </div>
    <div class="row justify-content-center mt-4">
      <div class="col-md-6">
        <h4>Send us a message:</h4>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light fixed-bottom">
    
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/Manoj0079940/Pharma/assets/149366208/74361394-b912-4491-9a64-3bc0f56641be)
![image](https://github.com/Manoj0079940/Pharma/assets/149366208/235b5bea-2f24-453e-a854-20d1c7fe7890)
![image](https://github.com/Manoj0079940/Pharma/assets/149366208/0a19130b-8996-4ca3-8dac-473ab40b8069)
![image](https://github.com/Manoj0079940/Pharma/assets/149366208/3a50e38e-97a7-4965-845d-49a3f8467e7e)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
