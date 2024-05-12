# Project Responsive Web Design using Bootstrap
## Date: 12.05.2024

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - SunPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">SunPharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to SunPharmacy</h1>
        <p>Sun Pharmaceutical Industries Ltd. (Sun Pharma) is the fourth largest specialty generic pharmaceutical company in the world 
            with global revenues of US$ 5.4 billion. Supported by 43 manufacturing facilities, we provide high-quality, affordable medicines,
             trusted by healthcare professionals and patients, to more than 100 countries across the globe.We manufacture and market a large 
             basket of pharmaceutical formulations covering a broad spectrum of chronic and acute therapies. It includes generics, branded 
             generics, specialty, complex or difficult to make technology-intensive products, over-the-counter (OTC), antiretrovirals (ARVs), 
             Active Pharmaceutical Ingredients (APIs) and Intermediates. Our broad portfolio of more than 2000 high quality molecules covers 
             multiple dosage forms, including tablets, capsules, injectables, inhalers, ointments, creams, and liquids.Every year, we sell over 
             30 billion doses covering neuro-psychiatry, cardiology, gastroenterology, anti-infectives, diabetology, oncology, ophthalmology, 
             dermatology, urology, nephrology and respiratory among others.The first among Indian pharmaceutical companies to realise and embrace 
             the importance of investing in research, we invest up to 6-8% of our global revenues into Research and Development (R&D) every year.
             Our core strength lies in our ability to excel in developing generics and technologically complex products backed by our dedicated 
             teams in formulations, process chemistry, and analytical development.Our capabilities extend beyond the development of differentiated
            products, including liposomal products, inhalers, lyophilized injections, nasal sprays, and controlled release dosage forms.Our R&D 
            team comprises over 2,800 people.</p>
      </div>
      <div class="col-md-4">
        
      </div>
    </div>
  </div>
  <body background="bcgpharm.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY JAYAVARSHA T(212223040075)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About SunPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">SunPharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#Reliability">Vision</a>
            <a class="dropdown-item" href="#Consistency">equipment</a>
            <a class="dropdown-item" href="#Innovation">usage</a>
            <a class="dropdown-item" href="#Integrity">research</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </ul>
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">Login</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Register</a>
      </li>
    </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About SunPharmacy</h1>
        <div id="Reliability">
          <h2>Reliability</h2>
          <p>Maintain efficiency & discipline in all processes & systems and fulfil the promises made to stakeholders.</p>
        </div>
        <div id="Consistency">
          <h2>Consistency</h2>
          <p>Endeavour to bring new products to the market & consistently deliver value to stakeholders.</p>
        </div>
        <div id="Innovation">
          <h2>Innovation</h2>
          <p>Implement new ideas & technologies to meet unmet needs and think ahead of times.</p>
        </div>
        <div id="Integrity">
            <h2>Intregity</h2>
            <ul>
              <li>* Do the right thing with conviction and without fear.</li>
              
              <li>* Practice honesty, impartiality and fairness at all times.</li>
              <li>* Adhere to strong ethical and moral standards.</li>
              <li>* Have courage to call out what is not right.</li>
            </li>
            </ul>
          </div>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>
  <body background="bcgpharm.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY JAYAVARSHA T(212223040075)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

product.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - SunPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">SunPharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="madmex.jpg" class="card-img-top" alt="Product 1" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 1</h5>
              <p class="card-text">✔ POWER-PACKED NUTRITION WITH 100% RDA OF VITAMINS AND MINERALS: The go-getter in you deserves all the nourishment you can get.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="para.jpeg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 2</h5>
              <p class="card-text">✔ FEVER CONTROL: Paracetamol is a commonly used medicine that can help treat pain and reduce a high temperature (fever).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="dolo.jpeg" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">PRODUCT NO : 3</h5>
              <p class="card-text">Healthkart Calcium Tablets For Men & Women With Vitamin D3 For Complete Bone Health & Joint (60 No).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY JAYAVARSHA T(212223040075)</p>
  </footer>
  <body background="bcgpharm.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - SunPharmacy</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">SunPharmacy</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback or any doubt or consultant and research information or further details and any equipments or chemicals or liquid based material purchase, please fill out the correct details below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>

          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          
          <div class="form-group">
            <label for="need">Your need</label>
            <input type="need" class="form-control" id="location" placeholder="Message">
          </div>
        
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4"><br>
        <h2>SunPharmacy</h2><br><br>
        <address>
          <strong>Company</strong><br>
          SUN@PHARMA<br><br>
          <strong>Address:</strong><br>
          No:4/272 Mogappair East, 
          Chennai
          600037
          TN,India<br><br>
          <strong>Email:</strong><br>
          sunpharma@gmail.com<br><br>
          <strong>Phone:</strong><br>
          +442454524<br>
        </address>
      </div>
    </div>
  </div>
  <body background="bcgpharm.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>DESIGNED AND DEVELOPED BY JAYAVARSHA T(212223040075)</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-05-12 115039.png>)
![alt text](<Screenshot 2024-05-12 115055.png>)
![alt text](<Screenshot 2024-05-12 121227.png>)
![alt text](<Screenshot 2024-05-12 115116.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
