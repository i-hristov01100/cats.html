<!DOCTYPE html>
<html lang="en">
<head>
    <link rel="stylesheet" href="styles.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" charset="UTF-8"/>
    <title>Cats for Adoption</title>
</head>
<body>

<br><br>

<!-- Main menu -->
<div class="menu">
    <a href="index1.html" class="button-class">Home</a>

    <!-- Dropdown only here -->
    <div class="dropdown">
        <button class="button-class">For adoption</button>
        <div class="dropdown-content">
            <a href="dogs.html">Dogs</a>
            <a href="cats.html">Cats</a>
        </div>
    </div>

    <a href="purebred.html" class="button-class">Purebred Pets</a>
    <a href="reptiles.html" class="button-class">Reptiles</a>
</div>

<br><br>

<div>
    <img src="img/cat-8540772_1280.jpg"
         onclick="alert('Choose Me!')" 
         alt="Cute cat for adoption" 
         width="500" 
         height="300">
</div>

<div style="display: flex; gap: 10px; justify-content: center;">
    <button class="button-class" onclick="window.location.href='index1.html'">Back</button>
    <button class="button-class" onclick="window.location.href='dogs.html'">Next</button>
</div>

<br>

<footer>All rights reserved!</footer>
<br>

<footer>
    <button type="button"
            onclick="alert('We are still developing this website. Please Excuse Us!')"
            class="new">
        Adoption Paper - Documents
    </button>
</footer>

</body>
</html>