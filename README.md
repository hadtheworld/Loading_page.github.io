# Loading_page.github.io
This is a loading page animation created as an introduction screen on of a web site or web page. created by using HTML and CSS only, animations done in CSS itself.


**The web page includes:**
  - one image is being used here as background image, which you can get from my GitHub repo mentioned at the end, or can use any of the image you want from google.
  - Rest of the styling is done using CSS only along with animation and background shape changing.
  - The code is well structured in HTML file in classes and div tags.
  - container class:-  is being used as a wrapper and container to hold in the entire animation and background.
  - loading class:-is being used to show background image and its animation.
  - bg class:- is being used to hold the background transitions.
  - The CSS styling applied are on these specific components which made each of the components complete in itself a.
  - This well structured format in HTML and specific styling in CSS will prevent the code from breaking in changing screen sizes, as the style and animation is solid with minimum codes.
  
  
** Detailed Description: only read if you want to know indepth about the web page**
Step-by-step documentation of the code:

  - The first line is a declaration of the document type and version of HTML being used.

  - The html tag is the root element of the document and sets the language of the page to "en" (English).

  - The head section contains meta information and links to external resources such as stylesheets.

  - Within the head section, there is a declaration of the character encoding being used for the page.

  - The title tag sets the title of the page, which appears in the browser's title bar.

  - The link tag references an external stylesheet called "loading_page_style.css" that contains the styling information for the landing page.

  - The body section contains the visible content of the page.

  - The div tag with class "container" sets up a container for the content of the landing page and defines its width and height.

  - The div tag with class "landing" creates the landing page area and sets the background image and a linear gradient that creates a semi-transparent black overlay. The background-position is set to center-top and an animation is applied to this element.

  - The div tag with class "bg" creates a solid background color and animates it by scaling it from 100% to 0% along the y-axis.

  - The @keyframes rule defines the animations for both "bganim" and "landinganim". The "bganim" animation scales the background color of the "bg" element from 100% to 0% along the y-axis over a duration of 2 seconds. The "landinganim" animation defines the clip-path of the "landing" element that animates it from a polygon shape that starts from the center-top to a polygon shape that ends at the center-bottom. The animation also moves the background position from center-top to center-bottom over a duration of 4 seconds.

  - The * selector applies margin and padding values of 0 to all elements in the page.

**Overall, the code defines the basic structure and styling of a landing page with an animated background that scales in and out.**
