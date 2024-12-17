# Ex.08 Design of Interactive Image Gallery
## Date:
17/12/2024
## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
    <title >
        Interactive Image Gallery
    </title>
    <style>
        body {
            font-family: Lemon, lemon;
            display: flex;
            flex-direction: column;
            align-items: center;
            margin: 0;
            background-size: cover;
            background-image: url("a.jpg");
        }

        h1 {
            margin-top: 20px;
            color: rgb(79, 242, 87);
            font-size: xx-large;
            font-style: italic;
        }

        .Gallery {
            display: flex;
            gap: 25px;
            max-width: 800px;
            margin-top: 200px;
            justify-content: center;
        }
    </style>

    <body>
        <h1>
            Interactive Image Gallery</h1>
        <div class="Gallery">
            <img src="cap.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="hulk.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="iron.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="thor.jpg" width="200" height="200" onclick="openImage(this.src)">
            <img src="black.jpg" width="200" height="200" onclick="openImage(this.src)">
        </div>
        <footer>
            <p>Designed and Developed by: V.VIVIN MATHEW(24001048) </p>
        </footer>
    
        <script>
            function openImage(src) {
                window.open(src, "_blank");
            }
        </script>
    </body>
</html>
```
## OUTPUT:

![alt text](<vivin/gallapp/static/Screenshot 2024-12-17 213931.png>)
![alt text](<vivin/gallapp/static/Screenshot 2024-12-17 213726.png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
