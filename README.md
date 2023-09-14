# youtube-clone
![Screenshot 2023-09-14 232616](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/beacd5a5-a5bf-446f-a4a3-53e2dc005360)
![Screenshot 2023-09-14 232627](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/b00ae90d-44b8-481f-92b6-58efbad40493)
![Screenshot 2023-09-14 232638](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/04fbaa42-96bf-465e-a68a-e60d3a5e2927)
![Screenshot 2023-09-14 232646](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/bd997540-05e2-44dc-a77b-633d8de03b49)
![Screenshot 2023-09-14 232700](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/64df669f-adb4-469a-899b-a426f72b9b6c)
![Screenshot 2023-09-14 232710](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/5cb27d60-4b07-4d1d-bd83-b805855056e7)
![Screenshot 2023-09-14 232727](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/d153a492-e450-4ffc-ba38-2af59910c7be)
![Screenshot 2023-09-14 232735](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/cdae5706-66e5-45d8-a09b-41ce91725bae)
![Screenshot 2023-09-14 232747](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/125877ff-5722-4c83-9630-40914e299805)
![Screenshot 2023-09-14 232752](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/d25546ff-32d1-48a4-925c-61d859c47e48)
![Screenshot 2023-09-14 232802](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/bb4e863b-997a-4f33-89a9-19a9f897b09d)
![Screenshot 2023-09-14 232812](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/598887cd-dacb-404e-b957-029a1108bfba)
![Screenshot 2023-09-14 232825](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/d5403cc4-b78e-49df-a9eb-e7e259e5bf15)
![Screenshot 2023-09-14 232838](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/ce4b0b2a-10cd-46fc-beea-15030cd12fc8)
![Screenshot 2023-09-14 232845](https://github.com/jaideepsingh0085/youtube-clone/assets/128147644/afb49885-e3ea-4840-b176-59b325671301)

Hosted Link : https://jaideepsingh0085.github.io/youtube-clone/

HTML :
<!DOCTYPE html>: Declares the document type as HTML5.
<html lang="en">: Defines the HTML document and sets the language to English.
<head>: Contains metadata about the web page.
<meta charset="UTF-8">: Specifies the character encoding of the document.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>YouTube Clone</title>: Sets the title of the web page.
<link rel="stylesheet" href="./styles.css">: Links an external CSS file for styling.
<body>: Contains the visible content of the web page.
<div class="navbar">: Defines the navigation bar section.
<div class="left">: Represents the left part of the navigation bar.
<svg>: Embeds an SVG icon for the menu.
<div class="mid">: Represents the middle part of the navigation bar.
<input type="text" placeholder="Search">: Creates a search input field.
<svg>: Embeds an SVG icon for search.
<div class="right">: Represents the right part of the navigation bar.
<svg>: Embeds SVG icons for various actions (e.g., notifications, apps, user profile).
<div class="container">: Contains the main content of the web page.
<aside class="aside">: Defines the sidebar section.
<div class="categories">: Represents a list of categories in the sidebar.
<div class="category">: Represents a single category item.
<span class="material-icons icons">: Embeds Material Icons in the categories.
<hr />: Adds a horizontal line to separate categories.
<main class="main">: Contains the main content area of the web page.
<h1>Recommended</h1>: Displays a heading for the recommended videos.
<div class="videos">: Contains a list of video elements.
<div class="video">: Represents an individual video entry.
<img src="...">: Displays a thumbnail image for the video.
<div class="details">: Contains details about the video.
<img src="...">: Displays the uploader's icon.
<div class="text">: Contains text details about the video.
<h3>...: Displays the video's title.
<a href="#">...: Creates a link to the video's source.
<span>...: Provides additional information about the video.
<div class="video"> to <div class="video">: Repetition of video entries for recommendations.

CSS :
* { margin: 0; box-sizing: border-box; }: Applies a universal reset, setting margin and box-sizing for all elements.

body { font-family: 'Roboto', 'sans-serif'; }: Sets the default font family for the entire document to Roboto or a generic sans-serif font.

svg { fill: #606060; }: Defines the fill color for SVG elements to a grayish color (#606060).

@font-face { ... }: Defines a custom font family ('Material Icons') and specifies its source for usage in the document.

.navbar { ... }: Styles the top navigation bar, specifying its width, height, and alignment properties.

.left { ... }: Styles the left side of the navigation bar, adjusting alignment and margins.

.yt-icon { fill: red; }: Changes the fill color for elements with the class "yt-icon" to red.

.mid { ... }: Styles the middle section of the navigation bar, setting the width and appearance of the search input and icon.

.right { ... }: Styles the right side of the navigation bar, arranging elements with a gap and margin.

.material-icons { ... }: Defines styling for elements with the class "material-icons," specifying font properties for icon rendering.

.icons { color: #606060; }: Sets the color for elements with the class "icons" to grayish (#606060).

.container { ... }: Styles the main container, determining its display, height, and overflow properties.

.aside { ... }: Styles the sidebar section, setting background color, width, and scroll behavior.

.categories { ... }: Styles the category list within the sidebar, arranging it in a column layout with margin.

.category { ... }: Styles individual category items, adjusting alignment, padding, and hover effects.

.category span:not(.icons) { margin-left: 15px; }: Adds a left margin to spans within category items, except those with the class "icons."

.category:hover { ... }: Defines the appearance of a category item on hover, changing the background color and cursor.

.aside::-webkit-scrollbar { display: none; }: Hides the scrollbar in the sidebar for WebKit browsers.

hr { ... }: Styles horizontal lines, specifying height, border, and background color.

h1 { ... }: Styles level 1 headings, adjusting font size, margin, and text color.

.main { ... }: Styles the main content area, setting its width, background color, padding, and border.

.videos { ... }: Styles the container for video elements, arranging them with flexbox properties.

.video { ... }: Styles individual video entries, specifying width and margin properties.

.thumb { ... }: Styles video thumbnail images, ensuring they cover their containers.

.uploader { ... }: Styles uploader icons, defining width, height, and border-radius.

.details { ... }: Styles the container for video details, typically containing uploader and text.

.text { ... }: Styles text elements within video details, arranging them in a column layout.

.text h3 { ... }: Styles heading elements within video details, adjusting font size, color, and margins.

.text a, span { ... }: Styles links and spans within video details, setting text decoration, font size, and color.
