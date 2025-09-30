Unique HTML Elements Used

template Element

Location: index.html, line 76
What it is: A mechanism for holding HTML that is not rendered when the page loads but can be instantiated later using JavaScript
How I'm using it: Created a reusable template for rocket preview cards that could be populated dynamically if needed
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/template

noscript Element

Location: All HTML files (bottom of each page)
What it is: Defines alternative content to display when JavaScript is disabled or not supported
How I'm using it: Showing a warning message to users if JavaScript is turned off in their browser
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/noscript

caption Element
Location: rockets.html
What it is: Specifies the title/caption of a table
How I'm using it: Providing clear titles for the rocket specification tables to improve accessibility and readability
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption

-----------------------------------------

Unique HTML Attributes Used 

loading Attribute

Location: Used on multiple images throughout all pages
What it is: Lazy loading attribute that defers loading of off-screen images
How I'm using it: Setting loading="lazy" on images to improve page load performance by only loading images when they're about to enter the viewport. The hero image uses loading="eager" to load immediately.
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#loading

sizes Attribute

Location: missions.html, line 47 (Crew Dragon image)
What it is: Defines a set of media conditions and indicates image sizes to use under those conditions
How I'm using it: Helping the browser determine which image size to load for responsive images based on viewport width
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#sizes

crossorigin Attribute

Location: rockets.html, line 147 (NASA SLS image)
What it is: Indicates whether CORS should be used when fetching the resource
How I'm using it: Set to "anonymous" to allow the image to be loaded from external sources without credentials
MDN Reference: https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/crossorigin
