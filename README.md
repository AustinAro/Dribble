# Project Responsive Web Design using Bootstrap
## Date:22/12/2024

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

# ph.html:
'''
<html>
<head>
    <title>Pharmacy Company</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>header {
        background-image: url('Screenshot 2024-12-17 191121.png');
        background-size: cover;
        color: white;
        text-align: center;
        padding: 50px 20px;
    }</style>
</head>
<body>

    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand text-light" href="#">Pharmacy Company</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-light" href="about.html">About Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-light" href="contact.html">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-12">
                <h1>Welcome to Pharmacy Company</h1>
                <p>Your trusted partner in health and wellness. Explore our range of medicines and health services.</p>
            </div>
        </div>
    </div>
    <div align="center">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="btn bg-success text-light" href="bsl.html">Register Now</a>
            </li>
        </ul>
    </div>

    <footer class="bg-light text-center py-3 mt-4">
        <div class="container">
            <p>Designed and Developed by Austin Aro A</p>
        </div>
    </footer>

</body>
</html>
'''
 
 # about.html:
 '''<html>
    <body>
        <div class="row mt-4" id="about">
            <div class="col-md-12">
                <h2>About Us</h2>
                <p>We are dedicated to providing top-quality pharmaceutical products and exceptional customer service.
                    Pharmacy is the science and practice of discovering, producing, preparing, dispensing, reviewing and monitoring medications, aiming to ensure the safe, effective, and affordable use of medicines. It is a miscellaneous science as it links health sciences with pharmaceutical sciences and natural sciences. The professional practice is becoming more clinically oriented as most of the drugs are now manufactured by pharmaceutical industries. Based on the setting, pharmacy practice is either classified as community or institutional pharmacy. Providing direct patient care in the community of institutional pharmacies is considered clinical pharmacy.
                    The scope of pharmacy practice includes more traditional roles such as compounding and dispensing of medications. It also includes more modern services related to health care including clinical services, reviewing medications for safety and efficacy, and providing drug information with patient counselling. Pharmacists, therefore, are experts on drug therapy and are the primary health professionals who optimize the use of medication for the benefit of the patients.
                    An establishment in which pharmacy (in the first sense) is practiced is called a pharmacy (this term is more common in the United States) or chemists (which is more common in Great Britain, though pharmacy is also used).[citation needed] In the United States and Canada, drugstores commonly sell medicines, as well as miscellaneous items such as confectionery, cosmetics, office supplies, toys, hair care products and magazines, and occasionally refreshments and groceries.
                    In its investigation of herbal and chemical ingredients, the work of the apothecary may be regarded as a precursor of the modern sciences of chemistry and pharmacology, prior to the formulation of the scientific method.
                </p>
            </div>
        </div>
        <footer class="bg-light text-center py-3 mt-4">
            <div class="container">
                <p>Designed and Developed by Austin Aro A</p>
            </div>
        </footer>
    </body>
</html>'''

# contact.html:
'''<html>
    <body>
        <div class="row mt-4" id="contact">
            <div class="col-md-12">
                <h2>Contact Us</h2>
                <p>Email: contact@pharmacycompany.com | Phone: +123 456 7890</p>
            </div>
        </div>
        <footer class="bg-light text-center py-3 mt-4">
            <div class="container">
                <p>Designed and Developed by Austin Aro A</p>
            </div>
        </footer>
    </body>
</html>'''

# registration html:

'''<html>
    <head>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    </head>
    <body>
        <script>
            function sfn()
            {
                document.getElementById("result").innerText="Registration Successful";
            }
        </script>
        <div align="center">
            <b>Enter your email </b>
            <input type="email" id="e1"><br>
            <b>Enter your Name </b>
            <input type="text" id="un"><br>
            <b>Enter your co.number</b>
            <input type="number" id="n"><br>
            <div align="center">
                <button class="btn btn-success" onclick="sfn()">Submit</button>
            </div><br>
            <b><p align="center" id="result"></p></b>
        </div>

        <footer class="bg-light text-center py-3 mt-4">
            <div class="container">
                <p>Designed and Developed by Austin Aro A</p>
            </div>
        </footer>
    </body>

</html>'''



## OUTPUT:

![alt text](<Screenshot 2024-12-22 153616.png>) 
![alt text](<Screenshot 2024-12-22 153633.png>) 
![alt text](<Screenshot 2024-12-22 153647.png>) 
![alt text](<Screenshot 2024-12-22 153557.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
