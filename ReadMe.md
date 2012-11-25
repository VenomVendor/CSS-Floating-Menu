Floating Menu using CSS3
========================

About:
------
   * Entire Project has been coded using CSS3.<br>
   * No Images are used.<br>
   * Font Used "Sans Narrow".<br>
   * Can be easily Customised.<br>
   * jQuery for Easing Effect
	  
	  
Usage:
======
CSS3
----
 * Each `div.content` will fit the entire height of the screen.<br>
 * There are 2 types of Menus with same functionality.
     * __Horizontal__ -  To use Horizontal REMOVE entire `.floating-menuV` from line 95 - 110.
     *  __Vertical__ - To use Horizontal REMOVE entire `nav.floating-menu a.hor` from line 126 - 128.
		
 * Use Anchor Tags to Scroll to the respective content.

__Example :__ 
<br>

     <a class="scroll button" href="#hme">Home</a>
  *   `#hme` is the anchor-tag, use the same tag(Case-Sensitive) in the `div.id="hme` <br>
  *   `class="scroll"` is the function which invokes smooth scroll effect using jQuery.



 *    To Change the height or width of the button change  line 160 - 163

					/* Main Adjustments */
						padding: 5px 10px;
						margin: 5px 10px;
					/* Main Adjustments */
					
 * Menu's Background Color can be adjusted in `.floating-menu` line 84 & 85.
*  Uncomment `background: transparent;` for transparent background.
		
jQuery
------
   * To increase/decrease the Scroll Speed enter value in `milli sec` at `.animate` currently it's value is `1000ms` or 1sec.
   * Adjust the landing position from top change the value at `scrollTop : $(this.hash).offset().top - 0` currently `0px` 
 *   Do not add `px` in the value above.
	
Copyrights:
-----------
Use it as you wish, no need of Adding name, Backlinking or Donating.<br>
If you wanna help me back, Share & Rate my [Android App](https://play.google.com/store/apps/details?id=veevee.kfc "KFC Store Locator").