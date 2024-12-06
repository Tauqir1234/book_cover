# Ex.06 Book Front Cover Page Design
# Date:28/10/2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
~~~
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>book cover</title>
        
    </head>
    <body>
        <style>
            body{
                font-size: 10px;
            }
            .banner{
                position: relative;
                width: 30%;
                height: 40%;
                margin:auto;
            }
            .banner img{
                
                width: 100%;
            }
            .heading{
                color: white;
                position: absolute;
                top: 1%;
                width: 100%;
                text-align: center;
                font-size: 3rem;
                text-shadow: 5px 5px 10px;
            }
            h1{
                text-align: center;
            }
            h3{
                color: azure;
                text-align: right;
                position: absolute;
                top: 80%;
                font-size: 1rem;
                width: 90%
            }
            p{
                color: white;
                position: absolute;
                top: 50%;
                width: 100%;
                text-align: center;
                font-size: 1.5rem;

            }
           
        </style>
        <h1>My Book</h1>
         <div class="container">
                <div class="row">
                    <div class="banner">
                        <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-10-18 180541.png" alt="img">
                        <h2 class="heading"><i> Ocean Of Stars </i></h2>
                        <p><b>Across the sea of space the stars are others sun</b></p>
                        <h3><i>Tauqir Ahmed S</i></h3>
                        
                    </div>
                </div>
         </div>
    </body>
</html>
~~~

# OUTPUT:
![Screenshot 2024-11-23 104818](https://github.com/user-attachments/assets/027b7be8-86b4-41dc-99d3-932eb4e1fbc9)
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     
# RESULT: 
The program for designing book front cover page using HTML and CSS is completed successfully.
