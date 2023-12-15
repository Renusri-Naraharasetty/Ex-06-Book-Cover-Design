# Ex-06-Book-Cover-Design
NAME : RENUSRI NARAHARASHETTY

REGISTER NUMBER : 23009126

DEPARTMENT : ARTIFICIAL INTELLIGENCE AND MACHINE LEARNING

## AIM:
Design the following book cover page using HTML and CSS.

## PROCEDURE:
# STEP 1:
Start with defining the document as html
# STEP 2:
In the html head tag, write the necessary contents needed for the book cover and separate them into containers to apply CSS styles for each container to where the content of the book cover goes.
# STEP 3:
For the given container names apply
background color

text size

font name

background image 

the author image with specified dimensions to fit in the book cover

the position and margin.
# STEP 4:
Body section consists of:

expert insight

book title 

subtitle

author 

publition 

edition
# STEP 5:
Run the program.

## CODE:
```
<!DOCTYPE html>
<html lang="en">

    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(https://res.cloudinary.com/dlseemi4e/image/upload/v1702617333/photo-1502723208559-c93671464db7_sei6bp.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:black;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:white;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color: whitesmoke;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            color: black;
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: black;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="https://res.cloudinary.com/dlseemi4e/image/upload/v1702617653/OIP_id2biz.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: white;">
            </div>
            <div class="author">
               <p><b>Coolen Hoover</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## OUTPUT:
![Alt text](<Screenshot 2023-12-15 111635.png>)


## RESULT:
Thus, a book cover has been designed and the code has been successfully executed.