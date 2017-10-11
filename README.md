# Zoomio- jQuery Image Zoom

**Description:**  **[jQuery Exit Intent Pop Up Script](http://www.dynamicdrive.com/dynamicindex8/exitpopup/)** is a modern, exit pop up script that's triggered when the user signals he's about to leave a page, by moving the mouse into the browser's location or toolbar. Great for capturing leads, the script supports 40+ intro animations and mobile fallback support.


## Installation
For npm and bower users, alternatively, run:

    $ npm install ddexitpop
    $ bower install ddexitpop

# Manual Install
**Step 1:**

Add the following code to the HEAD section of your page:

		<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.5.2/animate.min.css">
		<link rel="stylesheet" href="ddexitpop.css" />
		
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
		
		<script src="ddexitpop.js">
		
		/***********************************************
		* Exit Intent Pop Up Script (with mobile fallback)- By Dynamic Drive (www.dynamicdrive.com)
		* Please keep this notice intact
		* Visit http://www.dynamicdrive.com/ for full source code
		***********************************************/
		
		</script>
		
		<script>
		
		//*** Initialize DD Exit Pop Up Script:
		
		jQuery(function(){
			ddexitpop.init({
				contentsource: ['id', 'ddexitpop1'],
				fxclass: 'random',
				displayfreq: 'always',
				onddexitpop: function($popup){
					console.log('Exit Pop Animation Class Name: ' + ddexitpop.settings.fxclass)
				}
		
			})
		})
		
		</script>

**Step 2**
 The demo by default defines the pop up's content directly inline on the page. Add the following markup anywhere in the BODY of your page. It won't be visible until triggered:
 
          <div id="ddexitpop1" class="ddexitpop">
        	<h1>Hold On For Just One Second!</h1>
        	<p>Before you leave, download our FREE e-book that shows you how to create a blog, step by step, in under 20 minutes!</p>
        	<p>You'll learn:</p>
        	<ul>
        	<li>Pick a Web Host</li>
        	<li>How to select the best CMS</li>
        	<li>Install and Choose a Theme</li>
        	<li>Promote and Set Up Social Profiles for your Blog</li>
        	</ul>
        	<a class="calltoaction" href="#" onClick="ddexitpop.hidepopup()">Download Free E-Book</a>
        
        </div>

And that's it!  See the read **[documentation](http://www.dynamicdrive.com/dynamicindex8/exitpopup/)** on the supported options of this script when initializing it.