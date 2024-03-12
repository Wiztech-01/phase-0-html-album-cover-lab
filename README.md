# HTML Album Cover

## Learning Goals

- Use common HTML tags to produce a webpage based on a mock-up

## Introduction

Learning all the individual pieces that make up a web page is a necessary first
step in the process of learning HTML, but one of the best ways to solidify the
concepts we've learned is to apply concepts together. In this lab, your task
will be to update `index.html` based on commented notes in the file, using what
we've learned about text formatting and displaying images.

## Getting Started

**Fork and clone** this lesson into your local environment. Navigate into its
directory in the terminal, then run `code .` to open the files in Visual Studio
Code.

## Apply Header, Paragraph, Image and Span Tags

Pharrell isn't quite happy, he needs some help coding the album cover for his
hit song "Happy." His dev chops aren't quite as skilled as yours, so he's hired
you to take care of business.

Pharrell did provide us with a mock-up of what he would like to see for the
design of the album cover:

![Happy Album Cover](https://curriculum-content.s3.amazonaws.com/phase-0/html-album-cover-lab/album-cover-mockup.png)

In the industry, front-end developers are typically given specs just like this
from the product team and then asked to write the code to make a website look
just like the spec. Today, you're the developer and Pharrell is the product
team.

### Use SOURCE.md

Pharrell has provided us with the text for the album and all the legal
mumbo-jumbo to give credit where credit is due. You can find that text in
`SOURCE.md`. Again, this is a typical industry standard workflow, where the
developers are given a copy for the site from the product team.

Each line of text in this file corresponds to a note in `index.html` that will
indicate where you'll need to add this information. It will be up to you to pick
which HTML tags to use.

### Deliverables

Write your code in `index.html`. Your job is to make sure the text from
`SOURCE.md` makes it into `index.html` surrounded by the appropriate HTML tags.

You can see the images you'll be using in the 'images' folder, but you'll have
to write the correct URL paths (like `http://..../image-name`) in order for them
to display correctly. The comments in the `index.html` will help you with this.

You may not have encountered the `span` tag before, so if you are curious, take
a moment to [read up on some reference material] to better understand its use.

Open `index.html` in a separate browser tab to see your progress on the Album
Cover as you build it.

Run `npm test` to make sure you've met all the deliverables and passed the
tests.

## Conclusion

A lot of the formatting in this lab is done using CSS, or Cascading Style
Sheets, a language that defines styling for HTML. Before we can get to more
elaborate styling, though, it is important to have a strong understanding of
HTML fundamentals.

In this lab, we've tested that understanding by having you practice applying
headers, image, and paragraphs. Completing this lab means that you have a solid
foundation that we can build upon as we continue to learn about web development.

_Clap along if you feel_ you're getting the hang of HTML!

[read up on some reference material]:
  https://www.w3schools.com/tags/tag_span.asp

-------------------------------------------------------------------------------------


Using Your Browser's Developer Tools
Learning Goals
Examine the developer tools
Use the developer tools to locate and inspect elements
Use the developer tools to edit HTML
Introduction
By now, you're pretty familiar with HTML structural elements, and how they relate to each other on the page. You might even feel pretty comfortable writing your own valid HTML. But much of the time as developers, we'll be jumping in on projects that are already in progress. We'll need a way to view existing HTML and CSS, and potentially a way to play around with elements on live pages to see how we might potentially adjust things. Luckily for us, most browsers have those kinds of tools already built in, called developer tools, or dev tools for short. In this lesson, we'll look at the dev tools on Google ChromeLinks to an external site..

Examine the Developer Tools
The Developer tools that browsers provide you are a great way to experiment with HTML and CSS, and immediately see how those changes are rendered in the browser.

For this lesson, please open the Wikipedia page for Alan TuringLinks to an external site. in Chrome.

Once the page is open, right click on the title of the page — the header containing his name. You should get a list of options. We want to click on the one that says Inspect. This is going to bring up a window at the bottom of the page that contains all of the HTML that makes up the Wikipedia page.

Use the Developer Tools to Locate and Inspect Elements
If you hover over elements, you should see different colored boxes appear over different parts of the page. We're going to hover over the HTML until we find the section that contains the title of the page ("Alan Turing"). It should look something like this:

<h1 id="firstHeading" class="firstHeading">...</h1>
Use the Developer Tools to Edit HTML
There should be a drop down arrow next to the first <h1 ...> If you don't already see the text nested under that <h1>, click on the arrow to expose it. Right click that text and select Edit as HTML.

A new window will pop up in Dev Tools where we can actually go in and type. Try deleting "Alan Turing" and replacing it with "Puppies Puppies Puppies." Once you're done, just click outside of the text window, and take a look back at the header in the browser. It should now say "Puppies Puppies Puppies."

If you refresh the page, your text will disappear. We're just editing HTML in our own web browser, not on Wikipedia's web server. Feel free to scroll around on the page and play with all sorts of different HTML elements and see what happens.

Editing Images
Now, right click on Alan Turing's picture and choose "Inspect". Right click on the image tag in the HTML and again select Edit as HTML. Let's replace the entire <img> tag with another image from a website. For example, you might change it to this:

<img
  src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg"
  alt="Puppies"
/>
Your puppy image should now be displaying on the page, but it's pretty big. Let's add an attribute to our <img> tag to set the image's size. It should look like this:

<img
  src="http://images2.fanpop.com/image/photos/9400000/Aaaaaawwwwwwwwww-Sweet-puppies-9415255-1600-1200.jpg"
  width="200"
  alt="Puppies"
/>
This attribute sets the width of the image to 200px and adjusts the height accordingly. Much better!

Feel free to play with other HTML elements and watch things change on the page.

Bonus
If you want to attempt to change any of the styles of the page, take a look at the right-hand column. CSS, which stands for Cascading Style Sheets, manages all the styles of your page (think background color, font size, placement of different items on the page, etc).

Feel free to play around, check and uncheck boxes, change colors, change pixels. It's okay if you "mess things up". Just refresh the browser and it will all go back to how it was!
