# Grid-Structure


Hosted Link:- https://lok-ii.github.io/Grid-Structure/



![Screenshot 2023-08-24 185602](https://github.com/Lok-ii/Grid-Structure/assets/129180844/3de48f70-7cf8-4a97-b404-827f46ddf5a5)
		
  		The <head> section includes meta information, a link to an external stylesheet, and a title for the webpage.
		Inside the <body> section, the main content is wrapped in a <main> element.
  		The main content consists of a navigation bar (.navbar) and a series of image divs (.image elements) numbered from one to nine.



![Screenshot 2023-08-24 185543](https://github.com/Lok-ii/Grid-Structure/assets/129180844/cd068c57-5ae6-4615-b0c3-aeaeedacaeb0)
		
 		<div class="navbar"> element represents the navigation bar of the webpage.
		It contains navigation buttons ("Home," "About," "Menu," "Contact") and a logo image that together form the navigation menu of the site.

 		CSS used on .navbar:-

   			width: 100%: The navigation bar spans the full width of its container.
			display: flex: Flexbox layout is applied to the navigation items for flexible arrangement.
			justify-content: space-evenly: Navigation items are evenly spaced horizontally.
			align-items: center: Navigation items are centered vertically within the navigation bar.
			grid-area: 1 / 1 / 2 / 17: The navigation bar spans grid rows 1 to 2 and columns 1 to 17.
			background-color: white: The navigation bar has a white background color.
			padding: 3px: A small padding of 3 pixels is added around the navigation bar.

![Screenshot 2023-08-24 185550](https://github.com/Lok-ii/Grid-Structure/assets/129180844/51370c40-24d3-4512-8d06-e8b9e8d01e0a)
![Screenshot 2023-08-24 185556](https://github.com/Lok-ii/Grid-Structure/assets/129180844/3f8f3530-a806-4c82-b9c2-ccfc7b645803)

		The <div> elements with classes like .one, .two, etc., represent containers for images on the webpage.
		Each image div contains an <img> element that displays an image.
  			The image divs are used to showcase images within a grid layout.
			The images are given consistent styling, including padding, borders, and backgrounds, to ensure a uniform appearance.

  		CSS:-

   			.image img: These properties apply to images within the .image divs.
				
				padding: 2px: Adds a small padding around the image.
				width: 100%, height: 100%: Makes the image fill its container div completely.
				border: 3px solid black: Adds a black border around the image.
				background-color: white: Provides a white background behind the image.
			
   			.one: These properties apply to the first image div.
				
				grid-column: 1 / 4: Places the div in grid columns 1 to 3.
				grid-row: 2 / 3: Places the div in grid row 2.

 		Continuing in the same pattern, the rest of the image divs (two, three, four, five, six, seven, eight, nine) are positioned using the grid-area property, similar to how .one was positioned. Each image div contains an <img> element that showcases a different image.

 

