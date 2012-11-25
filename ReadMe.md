Floating Menu using CSS3
========================

About:
------
      Entire Project has been coded using CSS3.
	  No Images are used.
	  Font Used "Sans Narrow".
	  Can be easily Customised.
	  jQuery for Easing Effect.
	  
	  
Usage:
======
	CSS3
	----
		Each `div.content` will fit the entire height of the screen.
		
		There are 2 types of Menus with same functionality.
			* Horizontal -  To use Horizontal REMOVE entire `.floating-menuV` from line 95 - 110.
			* Vertical - To use Horizontal REMOVE entire `nav.floating-menu a.hor` from line 126 - 128.
		
		Use Anchor Tags to Scroll to the respective content.
			Example : <pre><a class="scroll button" href="#hme">Home</a></pre>
				* `#hme` is the anchor-tag, use the same tag(Case-Sensitive) in the `div.id="hme`
				* class="scroll" is the function which invokes smooth scroll effect.
			
		To Change the height or width of the button change  line 160 - 163
					/* Main Adjustments */
						padding: 5px 10px;
						margin: 5px 10px;
					/* Main Adjustments */
					
		Menu's Background Color can be adjusted in `.floating-menu` line 84 & 85.
				*  Uncomment `background: transparent;` for transparent background.
		
	jQuery
	------
		*  To increase/decrease the Scroll Speed enter value in `milli sec` at `.animate` currently it's 1000ms or 1sec.
		*  Adjust the landing position from top change the value at `scrollTop : $(this.hash).offset().top - 0` currently `0px`
	
Copyrights:
-----------
	Use it as you wish, no need of Adding name, Backlinking or Donating. If you wanna help me back, Share & Rate my [Android App](https://play.google.com/store/apps/details?id=veevee.kfc "KFC Store Locator")