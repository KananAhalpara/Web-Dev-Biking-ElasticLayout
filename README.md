# Web-Dev-Biking-ElasticLayout
Web Development assignment 2- elastic layout
<br><br>
Your site is ready to be published at https://kananahalpara.github.io/Web-Dev-Biking-ElasticLayout/.
<br><br>
ASSIGNMENT : AS FOLLOWS: 
<br>
Lab Assignment 2: Elastic Box Layout
 

Create an elastic layout that will hold varying amounts of content, and adapt to browser and font resizing.

You will be creating two columns with varying amounts of content. Select a WikiPedia article of any topic you like, but make sure it has a good amount of content. You will recreate this content in two “elastic” (a.k.a. “flexible”) columns.

COLUMN ONE: LOTS OF CONTENT

For the “long” column, the amount of content should be approximately 8–10 paragraphs or longer, with any arrangement of headings and subheadings you like. You must also include with at least two (2) images and two (2) pullquotes.

COLUMN TWO: VERY LITTLE CONTENT

You will create a “short” column with only 1–2 paragraphs and one image (or pullquote). The column must retain the same shape, and the overall layout should still retain two columns.

Basic Setup (feel free to expand/add)
Wrapper set to 80% width with 10% margin left and right
Inner columns set to 42% with 4% padding (left & right) and no margins. Float them both “left” and use “clear: both” on the footer. This will “clear” the float allowing the footer to flow below the columns. (This is the trickiest part of the assignment)
Guidelines
Must “react” well to browser window being expanded and shrunk manually by the user: 80% width with 10% margins left and right (be sure to check it yourself by resizing the browser width!)
Use max-width: 100% and height: auto on the <img> element
Use min-width to keep columns at least a certain width (try just setting the wrapper’s min-width to 320px and see what happens to everything!)
Must scale well when resized UP and DOWN two (2) steps using the browser’s “zoom” option (use % or Em to set font-sizes)
Fonts must have back-up typefaces specified, especially if using Google Webfonts!
Images must have "alt" attribute filled out
You must have background-color specified for elements that also use background-image
You must link to the original article in the footer for reference
