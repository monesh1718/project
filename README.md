# Project Responsive Web Design using Bootstrap
# Date:19/12/2025
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :
```
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>PharmEasy - Your Trusted Online Pharmacy</title>
  <link rel="stylesheet" href="{% static 'css/style.css' %}">
  <style>
    h1, h2, p {
      color: cyan;
    }
    body {
      border: 5px double greenyellow;
      padding: 10px;
      background-color: black;
      margin: 0;
    }
  </style>
</head>

<body>
<header style="text-align:center;">
  <h1>Pharmacy</h1>
  <p>Your Trusted Online Pharmacy</p>
</header>

<section>
  <h2 style="text-align:center;">Featured Products</h2>

  <div class="products">
    <div class="product-card">
      <img src="{% static 'images/para.jpg' %}">
      <h1>Paracetamol</h1>
      <h2>Rs.30</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'images/vit.jpg' %}">
      <h1>Vitamin C</h1>
      <h2>Rs.20</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'detoljpg' %}">
      <h1>detol</h1>
      <h2>Rs.50</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'cg.jpg' %}">
      <h1>cotton</h1>
      <h2>Rs.50</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'san.jpg' %}">
      <h1>sanitizer</h1>
      <h2>Rs.60</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'ban.jpg' %}">
      <h1>Bandage</h1>
      <h2>Rs.60</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'ors.jpg' %}">
      <h1>ors</h1>
      <h2>Rs.20</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'ace.jpg' %}">
      <h1>amoxicilian</h1>
      <h2>Rs.20</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'sa.jpg' %}">
      <h1>syruo-p</h1>
      <h2>Rs.120</h2>
    </div>

    <div class="product-card">
      <img src="{% static 'citi.jpg' %}">
      <h1>cetrizin</h1>
      <h2>Rs.10</h2>
    </div>
  </div>
</section>
</body>
</html>
```
css
.products {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.product-card {
  width: 200px;
  text-align: center;
  border: 2px solid green;
  border-radius: 10px;
  padding: 10px;
  background-color: white;
  transition: transform 0.3s ease;
}

.product-card:hover {
  transform: scale(1.1);
}

.product-card img {
  width: 100%;
  height: 150px;
  object-fit: cover;
}
```
# OUTPUT:
<img width="1920" height="1013" alt="tablets" src="https://github.com/user-attachments/assets/ae1bbd58-9510-419c-9ba8-c1a3aff5f570" />

# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
