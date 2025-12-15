# Ex.05 Book Cover Page Design
## Date:15/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
~~~
cover.html
<html>
 <head>
        <title>About The Book</title>
        <link rel="stylesheet" href="style.css">
    </head>

<body>
    <div class="container">
        <h1>About The Book</h1>
        <hr class="title-line">
        
            <div class="quote">
            "Chemistry is a branch of science that studies matter, its composition, properties, and the changes it undergoes. It helps us understand everything around us, from the air we breathe and the food we eat to medicines and materials like plastics and metals. Chemistry plays an important role in daily life by improving health, agriculture, energy, and the environment.".
            </div>
<p>
            "CHEMISTRY" is the science that explains how matter is formed and transformed.
            and through chemical reactions
             </p>
       
        
        <div class="author">
            <img src="WhatsApp Image 2025-12-15 at 23.21.34_d85e5a2c.jpg" class="aut-img">
            <div class="author-text">
                <h3>Aashik.A</h3>
                <p>
                   I am Aashik,Now am stydying in Saveetha Engineering College  CSE department odd junior 1st year. I 
am a computer science student in school who willingly chose this field.
                                    </p>
            </div>
        </div>
        <div class="footer">
            
            <span class="publisher">SEC publisher</span>
                
            
            <span class="price">Price:799</span>
        </div>

    </div>
</body>
</html>


style.css

body {
    margin: 0;
    padding: 0;
    background: white;
    
}

.container {
    width: 520px;
    height: 650px;
    background-image:url('jiraiya-naruto-naruto-dzhiraiia-ulybka.webp');
    background-size: cover;
    background-position: center;
    border: 20px solid black;
    border-radius: 25px;
    box-shadow: 0 20px 30PX rgb(225, 221, 221);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 50px;
    margin: 100px auto;
    
}


h1 {
    color: black;
    font-style: italic;
}



.title-line {
    border: none;
    height: 3px;
    background-color: black;  
    width: 2xpx;
    margin: 0 0 15px 0;
}


.quote {
    
     
    padding: 15px;
    margin: 25px 0;
    font-style: roman;
}

.author {
    display: flex;
    align-items: center;
    background: rgb(224, 221, 214);
    padding: 4px;
    border-radius: 3px;
    margin-top: 2px;

}

.aut-img {
    width: 70px;
    height: 80px;
    border-radius: 5px;
    margin-right: 15px;
    object-fit: cover;
}

.footer {
    margin-top: 20px;
    display: flex;
    justify-content: space-between;
    background: rgba(174, 204, 24, 0.862);
    color: green;
    padding: 12px 20px;
    border-radius: 4px;
    font-weight: bold;
}

.publisher {
    color: green;
}
~~~

## OUTPUT:
![alt text](<Screenshot 2025-12-15 232305.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
