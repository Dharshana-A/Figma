# Ex09 Event Registration Web Application
## Date:19/12/25

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro-max">
      <img class="bg-car" src="img/bg-car-1.png" />
      <p class="text-wrapper">DRIVEN BY INNOVATION,POWERED BY ENGNEERING</p>
      <div class="rectangle"></div>
      <div class="div">GET ON BOARD</div>
    </div>
  </body>
</html>
globals.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}
style.css
.iphone-pro-max {
  background-color: #645d5d;
  width: 100%;
  min-width: 225px;
  min-height: 553px;
  position: relative;
}

.iphone-pro-max .bg-car {
  position: absolute;
  top: 0;
  left: 0;
  width: 225px;
  height: 553px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.iphone-pro-max .text-wrapper {
  position: absolute;
  top: 84px;
  left: 49px;
  width: 161px;
  font-family: "Gudea-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro-max .rectangle {
  position: absolute;
  top: 209px;
  left: 61px;
  width: 120px;
  height: 18px;
  background: linear-gradient(90deg, rgba(197, 197, 197, 1) 0%);
  opacity: 0.5;
}

.iphone-pro-max .div {
  position: absolute;
  top: 209px;
  left: 77px;
  width: 133px;
  font-family: "Irish Grover-Regular", Helvetica;
  font-weight: 400;
  color: #e1e0e0;
  font-size: 14px;
  letter-spacing: 0;
  line-height: normal;
}

   
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 213833.png>)
## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
