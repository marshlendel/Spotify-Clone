# CIS 122: Spotify Clone

## Introduction

Everyone likes music, right? Odds are if you do, you've heard of Spotify. Today we're going to copy an older (and simpler) version of the Spotify home page:

All of the necessary assets and images are included in the starter code. Scroll to the bottom to see what it will look like when we are done!

# Exercise
_Note: The starter-code contains all the files, images, and text content needed to create the page. The text is in the `index.html` file, along with a spot for your css which holds the theme colors in a comment._

You will receive the images and resources in the starter-code directory. Write your CSS and HTML in the provided files, adding whatever HTML tags are needed. When you're done, submit all the files (images and html) as a single ZIP file.

### Hints

* Start by sketching out on a piece of paper the boxes that will form the different sections of the site. This will help you figure out what your HTML should look like.
* Then, break the HTML up with appropriate tags.
* Tackle the sections one by one, and don't be distracted by the other sections not looking correct yet.
* Use the inspector in Chrome! (Right click, select inspect.) This shows you what the browser thinks you told it to do. See the styles on the right side.
* You can see what the final product will look like in 3 ways:
	1. view the PDF version of what the page should look like in the end by viewing the file included in this repository, `lab-css-spotify-clone/spotify-prototype.pdf`
	2. [check out this link](https://github.com/josh7weaver/lab-css-spotify-clone/raw/master/spotify-prototype.pdf) to download the PDF version
	3. Scroll to the bottom of this page to see an image version!

### Instructions

The page is split into 4 sections. Add the appropriate HTML5 tags, classes, and/or id's you need to style the page to match the image (PDF linked to above.)

1. __Navbar__

	* Use a `nav` element for this section.
	* The navbar should be `position: fixed`.
	* Float the image left, and float a `ul` with the links right.

2. __Large image background with text__

	* Check out [this guide](https://css-tricks.com/centering-css-complete-guide/) on centering things.
	* I recommend using a background image instead of an `<img>` tag

3. __"What's on Spotify" section__

	* It looks like the `div`s take up about a third of the container each. How can you represent this in code?

4. __Green Footer Section__

	* Use a `footer` tag for the container element
	* It looks like we have 2 main pieces, a `div` with the text content, and the image of the Spotify player. Position these according to the surrounding green `footer`.
	* Position the Spotify logo absolutely according to the Green `div`.

## Final product
![Spotify image](https://github.com/josh7weaver/lab-css-spotify-clone/raw/master/snapshot.png)