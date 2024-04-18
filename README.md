HTML
1. I learned about the HTML5 <table> doing this assignment. I found the new table API to be very helpful and helped me modulate my code to make it more readable and maintable.
2. I learned about default user agent styling that can come from the specific browser you use. I always assumed the default styling the browsers provided was default to HTML not the browser you use, so I found it interesting seeing how my website would change on different browsers as they used different default styling sheets.
3. I learned about importing fonts from an external source, and using the <link> tag to fetch the fonts while loading the page. I didn't know that I could specify external fonts and just provide an endpoint that the user would automatically download for the page.

CSS
1. I learned about specificity and how to properly override styles using higher specificities (IDs/Classes). I used to think that a higher specfiicity was just controlled by the order of the rules in the CSS stylesheet, but I learned that it is dependent on the specifiers used.
2. I learned about CSS Pseudo-CLasses such as :hover, :visited, and :active which allowed me to make some cool transitions and styling when hovering a link or when a user has already visited a link.
3. I learned about using the > specifier and the quirks that it comes with. I assumed that > meant direct descendents and not all descendents of some element. This bug came up while I writing CSS as I had applied a div > li rule which was applying to my nested <ol> as they were deeply nested within a div, and this had higher specificity than the <li> rule I was using.
