Project Title: Contact form With Captcha

Organization: Code Clause

Project Manager: Mr. Pratik Kate

Description: Designing a contact form using HTML and integrating Captcha on the page  

Responsibilities: Design the Contact form with Captcha Frontend.

Duration: 1 month: 1-June-2023 to 30-June-2023

Structure of Contact form with Captcha Frontend website:

Main File: ContactForm.html

	<!DOCTYPE html>
	<html>
	<head>
	    <meta charset="UTF-8">
	    <meta http-equiv="X-UA-Compatible" content="IE=edge">
	    <meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <link rel="stylesheet" href="./style.css">
	    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
	    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
	    
	</head>
	<div class="Contact-form" >
	    <div class="formtitle">
	        Get In Touch
	    </div>
	    
	    <div class="forminput">
	        <label for="name"></label>
	        <input type="text" id="name" placeholder="Name" required>
	    </div>
	
	    <div class="forminput">
	        <label for="email"></label>
	        <input type="email" id="email" placeholder="Email" required>
	    </div>
	
	    <div class="forminputm">
	        <label for="message">Message</label>
	        <div class="preview"></div>
	        <input type="text" id="message" placeholder="Enter your query" required>
	       <!-- <textarea rows="5" cols="60" name="text" placeholder="Enter text"></textarea> -->
	    </div>
	    
	    <div class="captcha">
	        <div class="preview"></div>
	        <div class="captcha-form">
	            <input type="text" id="catcha-form" data-toggle="collapse" placeholder="Enter captcha text">
	        </div>
	        <button class="captcha-refresh">
	            <i class="fa fa-refresh" >Refresh</i>
	        </button>
	    </div>
	    <div class="submit-btn">
	        <button id="submit">SUBMIT</button>
	    </div>
	</div>
	<footer>
	    <script src="app.js"></script>
	    
	</footer>
	</html>
	
	*Style.css: The style.css file is written to style the background of the website and container
	            which stores the input label and tasks.
	
	*app.js: The app.js is used to provide an interactive interface to our Contact form along with a regenerating captcha  		 
                 addEventListener() method of dom.

	
