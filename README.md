# Ex.06 Book Front Cover Page Design
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
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
            color:antiquewhite;(84, 65, 150);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        
            background-image: url(/static/images/back.png);
            background-size: cover;
        }
            

        .toptext{
            color:rgb(218, 22, 218);

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: rgb(206, 98, 98);
            display: inline;
            position: relative;
            text-align: left;
            color:navajowhite;(12, 67, 248);
            top:130px;
            
            font-family:'ink free';
            font-size: large;
        }
        .booktitle{
            font-family: 'gabriola', monospace;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 19px;
            color:red;
        
        }
        
        
        .publisher{
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: medium;
            position: relative;
            color:thistle;
            top:105px;
            left:330px;
        }
        .edition{
            color:aquamarine;
            font-size: large;
            font-family: 'ink free';
            text-align: right;
            position:relative;
            top:25px;

        }
        .subtitle{
            font-family:'Segoe script';
            font-size: large;
            text-align: center;
            position: relative;
            top:17px;
        }
        .photo{
            position: relative;
            top: 65px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        .text-container {
            position: absolute;
            top: 395px;
            left: 550px; 
            color:aqua;
            font-size: x-large;
            font-family: 'cambria math',sans-serif ;
        }

         .text-containers {
            position: absolute;
            top: 435px;
            left: 590px; 
            color:aqua;
            font-size: x-large;
            font-family: 'cambria math',sans-serif;
        }

        .text-containerss {
            position: absolute;
            top: 470px;
            left: 635px; 
            color:aqua;
            font-size: x-large;
            font-family:  'cambria math',sans-serif;
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
                <hr style="color: aqua;">
            </div>

            <div class="subtitle">
                TiNy  chAnGEs
            </div>

            <div class="subtitle">
                ReMarKAblE  rEsulTs....
            </div>    

            <div class="booktitle">
                <h1>Ethical Hacking </h1>
            </div>

            <div class="subtitle">
                easy way to learn Ethical Hacking and improve your skill
            </div>
            

            <div class="photo">
                <img src="/static/images/my.jpg" width="130" height="145" alt="">
            </div>
            
            <div class="text-container">
               <p> Improve </p> 
            </div>

            <div class="text-containers">
               <p> your </p> 
            </div>

            <div class="text-containerss">
               <p> Skill</p> 
            </div>

            <div class="author">
               <p><b>Cover page by </b></p>
            </div>
            
            <div class="author">
               <p><b>PERARASU M</b></p>
            </div>

            <div class="publisher">
                Packt
            </div>
            
            <div class="edition">
                <b>PERARASU M</b>
            </div>
            
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## OUTPUT:
![OUTPUT](./out.png)



## HTML VALIDATOR:
![HTML VALIDATOR](./valid.png)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
