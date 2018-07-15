# elwood
CS50-W Project 0 created by Gloria Binette aka RedefinedVariable

Website contains four .html pages and a custom stylesheet 
	*index.html, p0-column.html, p0-lists.html, p0-table.html, styles.css
	* Navigation is offered via 2 options per page. Buttons on all pages have bootstrap tooltips except p0-Lists which demonstrates the native tooltips
	  - Nav element with a row of divs styled as button-esq use hrefs to navigate.        
	* All pages have 
		image in upper left
		divs that draw upon SCSS inheritance using extend %containers-shared;... 
		use scss variables for colors and font-size
		use classes and IDs to control styles
		use a mixin ClearFix to position divs
		*Hideous colors for the buttons as they are being resized to aid in testing the responsive design.
	* Pages also have a debug div that is purposely left visible to facilitate checking responsiveness. 
		Using javascript width of the screen is displayed. After resizing, one needs to refresh the page to update the value.
	* Page notes
		index.html 
			css styles controling paragraph, span via ID, unordered list 
		p0-column.html
			has bootstrap grid with divs acting as rows, each containing divs that use col-xx-n to control the layout
			media queries used to change font-size and div content
		p0-lists.html
			Nested list using scss nesting to control the bullet styles	
			contains inline link to an external page
		p0-table.html
			Contains old school table with alternating row color.	
		styles.css 
			variables used in scss are compiled to have proper values in the css
			@media queries, inheritance via 'extend'
