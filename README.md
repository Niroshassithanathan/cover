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
        
            background-image: url(/static/images/dna.jfif);
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
                <h1>ATOMIC HABITS </h1>
            </div>

            <div class="subtitle">
                An EasY wAy AnD pROvEn WAys TO BuIld gOoD haBIts & bReAk baD ONes
            </div>
            

            <div class="photo">
                <img src="/static/images/me.jfif" width="130" height="145" alt="">
            </div>
            
            <div class="text-container">
               <p>HaBits </p> 
            </div>

            <div class="text-containers">
               <p> deFiNEs </p> 
            </div>

            <div class="text-containerss">
               <p> yOu....</p> 
            </div>

            <div class="author">
               <p><b>Cover page by </b></p>
            </div>
            
            <div class="author">
               <p><b>NIROSHA SITHANATHAN</b></p>
            </div>

            <div class="publisher">
                Packt>
            </div>
            
            <div class="edition">
                <b>NIROSHA SITHANATHAN</b>
            </div>
            
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## OUTPUT:
## CLIENT OUTPUT:

<img width="524" alt="bookcover" src="https://github.com/Niroshassithanathan/cover/assets/121418437/5688a2e0-7e4f-4d68-bbf6-f7b22093a2e3">

## SERVER OUTPUT:

<img width="613" alt="out1" src="https://github.com/Niroshassithanathan/cover/assets/121418437/1b3c01f2-d60a-4d50-a7ce-d24002888116">

## HTML VALIDATOR:

<img width="919" alt="coverhtml" src="https://github.com/Niroshassithanathan/cover/assets/121418437/6cb7e986-16fe-41f2-a603-738688646393">

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
