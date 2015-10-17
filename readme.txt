This is a site for Prosocial Digital Marketing Agency, Wellington
Made by Emily Mabin Sutton

TO DO
9. All the left alignments do not have enough buffer between them and the edge of the screen. work out why
8. Make sure all forms SEND somewhere
7. Change favicon to PS or something better
6. Work out how to make 'our services' bigger than 'prosocial academy'
5. Make all the links between pages work and hide all the non-useful domains
4. Make 'get in touch form' - take off block on right hand side
- make it send a reply saying "thanks for your message, we endeavour 2 days"
- make it actually send us an email
-make all fields compulsory
- make the option for 'type of query' a drop down / tick box with 'business, academy, or other'
3. Make nav icons shade blue when on that specific page

PROGRESS LINE  - DONE BELOW THIS LINE

2. Change colour theme to blue, grey, black, white
bright red #ff0000
darkest red #D73C47

lightest red #E0676F
background colour #DB515B

darkest blue #002E8A
normal blue #003399
light blue #325BAD

other blue #1947A3 (lighter than 325bad)

1. Map out site pages

HOME
FOR CLIENTS
PROSOCIAL ACADEMY


Dev logs:

30 September 15
Changed the header section so it makes sense & is the same across the site.
Unsuccessfully tried to edit the image so you can see the green door on mobile
 - still can't seem to get that working.
Deleted some random files we don't need


Tried to make a universal header. Looking like SSIs should work -
 can't test on python server but can test it if I try get it on the real site
 if not, look for a template
 would be great to have a template anyway - it would be much easier to edit.



deleted code


	<div class="width">

    		<h1><a href="/">pro<strong>social</strong></a></h1>

		<nav>

    			<ul class="sf-menu dropdown">


        			<li class="selected"><a href="index.html">Home</a></li>

            			<li>

					<a href="examples.html">Style examples</a>

					<ul>
                				<li><a href="three-column.html">Three Column</a></li>
						<li><a href="one-column.html">One Column</a></li>
                    				<li><a href="text.html">Text page</a></li>
                			</ul>

            			</li>

	     			<!-- <li><a href="#">Services</a></li> -->

				<li>

					<a href="#">Products</a>

					<ul>
                				<li><a href="#">Product One</a></li>
                   				<li><a href="#">Product Two</a></li>
                   				<li><a href="#">Product Three</a></li>
                			</ul>

            			</li>

				<li><a href="#">Contact</a></li>
       			</ul>


			<div class="clear"></div>
    		</nav>
       	</div>

	<div class="clear"></div>


    </header>


    <div id="intro">
>>>>>>> parent of 1f6ee4d... Merge pull request #4 from emilology/master
