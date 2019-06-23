<!DOCTYPE html>
<html>
	<head>
		<!-- Title here -->
		<title>Martin Luther Theme Documentation</title>
		<!-- Description, Keywords and Author -->
		<meta name="description" content="Your description">
		<meta name="keywords" content="Your,Keywords">
		<meta name="author" content="ResponsiveWebInc">
		
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		
		<!-- Styles -->
		<!-- Bootstrap CSS -->
		<link href="css/bootstrap.min.css" rel="stylesheet">
		<!-- Custom CSS -->
		<link href="css/style.css" rel="stylesheet">
		
		<!-- Favicon -->
		<link rel="shortcut icon" href="#">
	</head>
	
	<body>

		
		<div class="container">
			<div class="main">
				<div class="row">
					<div class="col-md-2">
					
						<div class="sidebar">
							<!-- Project name -->
							<h3>Martin Luther</h3>
							<ul>
								<li><a href="#home">Home</a></li>
								<li><a href="#files">File Structure</a></li>
								<li><a href="#editing">Editing</a></li>
								<li><a href="#fonts">Fonts & Icons</a></li>
								<li><a href="#add-page">Add New Section</a></li>
								<li><a href="#plugins">Plugins</a></li>
							</ul>
						</div>
						
					</div>
					<div class="col-md-10">
					
						<div class="mainbar">
						
						
						
							<!-- Home -->
							<h3 id="home">Documentation Overview</h3>
								
								<p>To edit Martin Luther theme, basic knowledge about HTML, CSS, JS & Bootstrap is required. You can learn HTML, CSS and JS from <a href="http://www.w3schools.com/">W3Schools</a>. You can learn Bootstrap by visiting <a href="http://getbootstrap.com/">official site</a>.</p>
								
								<p>All components used in the theme are well commented. If you like to use any component then open the HTML file and refer the code.</p>
								
								<div class="alert alert-danger"><strong>Note:</strong> Before you make any changes, take a backup of all files and folders.</div>
							
								
							<hr />
							


<!----------------------------------------------------------------------------------------------------------->														
							
							
							
							<!-- File structure -->
							<h3 id="files">File Structure</h3>

<figure class="highlight">
<pre>
<code class="language-bash" data-lang="bash">
martin-luther/static
	|-- index.html
	|-- blog.html
	|-- blog-2.html
	|-- blog-3.html
	|-- blog-details.html
	|-- css/
	|   |-- style.css
	|   color |-- default.css
	|	  |-- black.css
	|	  |-- blue.css
	|	  |-- brown.css
	|	  |-- green.css
	|	  |-- lblue.css
	|-- img
	|   |-- All Images in this folder
	|-- js/
	|   |-- custom.js
	|   |-- html5shiv.min.js
	|   |-- jquery.js
	|   |-- jquery.nav.js
	|   |-- respond.min.js
	|-- plugin/
	|   |-- bootstrap
	|   |-- font-awesome
	|   |-- mixitup
	|   |-- parallax
	|-- video/
----------------------------------

</code>
</pre>
</figure>
							
								<p>Theme consists of 3 main folders namely <em>css, img, js & Plugin</em>. <br />
								Inside <em>css</em> folder you will find styles used in this theme. There is one more folder called <em>color</em> which has theme color options. <em>style.css</em> is main stylesheet. <br />
								Inside <em>img</em> folder you will find all images used in the theme.<br />
								Inside <em>js</em> folder you will find all Javascript files. <em>custom.js</em> is the main js file. To add your own code you need to create your own js file.
								</p>
							
							<hr />
							


<!----------------------------------------------------------------------------------------------------------->		

					

							
							
							<!-- Editing -->
							<h3 id="editing">Editing</h3>
							
								<p>To edit files you need any code editor. I recommend using Notepad++ and Sublime Text.</p>
								
								<strong>Add Custom Styles</strong>
								<p>To add custom styles, create new style sheet in <em>css</em> folder. Include the style file before the closing tag of <code>&lt;head&gt;</code>. Make sure that you are including this new file after <em>style.css</em></p>
								<p>If you want to add any extra CSS files, copy the file to <em>css</em> folder and link it before <em>style.css</em>.</p>
								
								<pre>
&lt;link href=&quot;css/FILE-NAME.css&quot; rel=&quot;stylesheet&quot;&gt;									
								</pre>
								
								<hr />
								
								<strong>Add Custom JavaScript</strong>
								<p>To add JS, just create a new java script file in <em>js</em> folder. Include the newly created js file before the closing tag of <code>&lt;body&gt;</code>. Make sure that you are including this new file after <em>custom.js</em>. Alternatively you can also include Javascript code directly to the html file by enclosing the code in <code>&lt;script&gt; ...your code... &lt;/script&gt;</code> and adding this above the closing tag of <code>&lt;body&gt;</code></p>
								<p>If you want to add any extra JS files, copy the file to <em>js</em> folder and link it before <em>custom.js</em>.</p>

								<pre>
&lt;script src=&quot;js/FILE-NAME.js&quot;&gt;&lt;/script&gt;								
								</pre>
							
								<hr />
								
								<strong>Editing HTML</strong>
								<p>Almost all html codes in this theme are neatly commented. All you need to do is to read the comment and modify the content based on your need.</p>
								
								<hr />
							
							
<!----------------------------------------------------------------------------------------------------------->
														
			
							<!-- Fonts -->
							<h3 id="fonts">Fonts</h3>
							
								<p>This theme uses <a href="http://fortawesome.github.io/Font-Awesome/">Font Awesome Icons</a> for Icons and <a href="http://www.google.com/fonts">Google Web Fonts</a> for Fonts.</p>
								
								<!-- Icon font -->
								<strong>Icon Font</strong>
								<p>Refer <a href="http://fortawesome.github.io/Font-Awesome/">Font Awesome Icons</a> for list of fonts. To use any fonts in the theme, you need to use the following code.</p>
								
								<pre>
/* Latest version */
&lt;i class=&quot;fa fa-XXXX&quot;&gt;&lt;/i&gt;
								</pre>
								
								
								<hr />
								
								
								<!-- Web Font -->
								<strong>Web Font</strong>
								<p>This theme uses <em>Poppins</em>. To add or change font visit <a href="http://www.google.com/fonts">Google Web Fonts</a>, Choose the font, Copy the <em>STANDARD</em> code. Paste it in your HTML file in side of &lt;head&gt;&lt;/head&gt; tag.</p>
								
								<pre>&lt;link href="https://fonts.googleapis.com/css?family=Poppins:300,300i,400,400i,500,500i,600,600i,700,700i,800,800i" rel="stylesheet"&gt;</pre>
							
								<hr />
							
							
							
<!----------------------------------------------------------------------------------------------------------->	



							<!-- XXXXXXXXXXXXXXXXXXXX -->
							<!-- If the theme is single page theme, then remove this. -->
							<h3 id="add-page">Add New Section and Navigation</h3>

								<p>This is one page theme if you wnat to create new section you need to follow below points</p>
								<ul>
									<li>
										1. Add Link in main navigations
										<pre>&lt;li&gt;&lt;a href="#Your_Section_Name"&gt;Your Section Name&lt;/a&gt;&lt;/li&gt;</pre>
									</li>
									<li>
										2. Create your section
										<pre>&lt;section id="Your_Section_Name"&gt;&lt;div class="container"&gt;Your content here&lt;/div&gt;&lt;/section&gt;</pre>
									</li>
								</ul>

								<hr />
							
							<hr />
<!----------------------------------------------------------------------------------------------------------->


							
							<!-- XXXXXXXXXXXXXXXXXXXX -->
							<!-- Remove the plugins which are not used in this theme -->
							<!-- Plugins used -->
							<h3 id="plugins">Plugins</h3>
							
								<p>This theme uses following plugins. To customize the plugins, you need to refer the official Plugin documentation found in below links.</p>
								<ul>
									<li>Bootstrap - <a href="http://getbootstrap.com">http://getbootstrap.com</a></li>
									<li>jQuery - <a href="http://jquery.com">http://jquery.com</a></li>
									<li>One Page Nav - <a href="http://github.com/davist11/jQuery-One-Page-Nav">http://github.com/davist11/jQuery-One-Page-Nav</a></li>
									<li>Mixitup - <a href="https://www.kunkalabs.com/mixitup/">https://www.kunkalabs.com/mixitup/</a></li>
									<li>Font awesome icon - <a href="http://fortawesome.github.io/Font-Awesome/">http://fortawesome.github.io/Font-Awesome/</a></li>
									<li>Simple Parallax Scrolling  - <a href="http://pixelcog.github.io/parallax.js/">http://pixelcog.github.io/parallax.js/</a></li>
									<li>Owl Carousel - <a href="https://owlcarousel2.github.io/OwlCarousel2/">https://owlcarousel2.github.io/OwlCarousel2/</a></li>
								</ul>
							
							
<!----------------------------------------------------------------------------------------------------------->														
							
							
							<!-- Changelog 
							<h3 id="changelog">Changelog</h3>
							
								<strong>Version 1.0:</strong>
								<ul>
									<li>Initial Release.</li>
								</ul>
							-->
							
							
						</div>
						
					</div>
				</div>
			</div>
			<br />
			<div class="footer text-center">
				Copyright 2017 - Martin Luther</a>
			</div>
		</div>
		
		
		<!-- Javascript files -->
		<!-- jQuery -->
		<script src="js/jquery.js"></script>
		<!-- Bootstrap JS -->
		<script src="js/bootstrap.min.js"></script>
		<!-- Respond JS for IE8 -->
		<script src="js/respond.min.js"></script>
		<!-- HTML5 Support for IE -->
		<script src="js/html5shiv.js"></script>
	</body>	
</html>