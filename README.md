# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

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

    <!DOCTYPE html>
    <html lang="en">
    
    <head>
      <title>Book Cover</title>  
      <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto">
      <link rel="stylesheet" href="styles.css" />  
    </head>
    
    <body>
      <div class="container">
        <div class="header">
          <label>EXPERT INSIGHT</label>
        </div>
        <div class="title">
          <label>Responsive Web Design with HTML5 and CSS</label>
        </div>
        <div class="description">
          <label>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</label>
        </div>
        <div class="edition">
          <label>Third Edition</label>
        </div>
        <div class="author">
          <img src="images/author.jpg" />
          <label>Dheebash Sai Ramesh</label>      
        </div>
      </div>
    </body>
    
    </html>

    body {
	font-family: 'Roboto';
	margin: 0;
	padding: 0;
	background-color: #f0f0f0;
	color: #333;
	line-height: 1.6;
	}

    .container {
    	position:relative;
    	display: flex;
    	flex-direction: column;
    	width: 760px;
    	height: 980px;
    	margin: 20px auto;
    	padding: 0px;
    	background-image: url('images/background.jpeg');
    	background-repeat: no-repeat;
    	box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }
    
    .header {
    	position: relative;
    	display: flex;
    	margin:0px;
    	margin-top: 48px;
    	padding: 8px 48px;
    	font-size: 18px;
    	font-weight: bold;
    	width:160px;
    	border-bottom: 2px solid #e07102;
    }
    
    .title {
    	position: relative;
    	display: flex;
    	margin:0px;
    	margin-top: 48px;
    	padding: 8px 48px;
    	font-size: 72px;
    	font-weight: bold;
    	width:540px;
    	line-height: 100px;
    }
    
    .description {
    	position: relative;
    	display: flex;
    	margin:0px;
    	margin-top: 48px;
    	padding: 8px 48px;
    	font-size: 20px;
    	font-weight: bold;
    	width:520px;
    }
    
    .edition {
    	position: relative;
    	display: flex;	
    	flex-direction: row;
    	margin:0px;
    	margin-top: 60px;
    	padding: 8px 48px;
    	font-size: 32px;
    	font-weight: bold;
    }
    .author {
    	position: absolute;
    	right:0px;
    	bottom:60px;
    	display: flex;	
    	flex-direction: column;
    	align-items: center;
    	justify-content: space-between;
    	margin:0px;
    	margin-top: 0px;
    	padding: 8px 48px;
    	font-size: 18px;
    	font-weight: bold;	
    }
    .author img {
    	width:120px;
    	border-radius: 60px;
    	padding: 16px;
    }

## OUTPUT:
Output/bookcover.png

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
