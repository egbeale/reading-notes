# Structuring Web Pages with HTML

## HyperText Markup Language

- defines meaning and structure of web content.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. 

### ELEMENTS and TAGS
- HTML consists of a series of ELEMENTS, which are used to enclose or wrap different parts of the content to make it appear a certain way, or act a certain way. 

- Tags begin or end an element in source code, whereas elements are part of the DOM, the document model for displaying the page in the browser.

- The opening tag:
    - This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

- The closing tag: 
    - This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.

- The content: 
    - This is the content of the element, which in this case, is just text.

- The element: 
    - The opening tag, the closing tag, and the content together comprise the element.

---

- DOCTYPE is a required preamble. In the mists of time, when HTML was young (around 1991/92), doctypes were meant to act as links to a set of rules that the HTML page had to follow to be considered good HTML, which could mean automatic error checking and other useful things. However these days, they don't do much and are basically just needed to make sure your document behaves correctly. That's all you need to know for now.

- The HTML element wraps all the content on the entire page and is sometimes known as the root element.

- Head element acts as a container for all the stuff you want to include on the HTML page that isn't the content you are showing to your page's viewers. This includes things like keywords and a page description that you want to appear in search results, CSS to style our content, character set declarations, and more.

- This element sets the character set your document should use to UTF-8 which includes most characters from the vast majority of written languages. Essentially, it can now handle any textual content you might put on it. There is no reason not to set this and it can help avoid some problems later on.

- Title element. This sets the title of your page, which is the title that appears in the browser tab the page is loaded in. It is also used to describe the page when you bookmark/favorite it.

- Body element. This contains all the content that you want to show to web users when they visit your page, whether that's text, images, videos, games, playable audio tracks, or whatever else.

## IMAGES
> < img src="images/firefox-icon.png" alt="My test image >

- Embeds an image into our page in the position it appears. It does this via the src (source) attribute, which contains the path to our image file.

- alt (alternative) attribute. In this attribute, you specify descriptive text for users who cannot see the image.

## HEADINGS

Heading elements allow you to specify that certain parts of your content are headings — or subheadings

- < h1 >My main title</ h1 >
- < h2 >My top level heading</ h2 >
- < h3 >My subheading</ h3 >
- < h4 >My sub-subheading</ h4 >

## PARAGRAPHS

- < p > 
- < / p >

## LISTS

- Unordered lists - wrapped in < ul > element. 
- Ordered lists - wrapped in < ol >
- each item inside list gets < li >

## LINKS

< a href="https://www.mozilla.org/en-US/about/manifesto/">Mozilla Manifesto</ a >


## NESTING ELEMENTS

- You can put elements inside other elements too — this is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word "very" in a <strong> element, which means that the word is to be strongly emphasized.

## SEMANTICS

- In programming, Semantics refers to the meaning of a piece of code — for example "what effect does running that line of JavaScript have?", or "what purpose or role does that HTML element have" (rather than "what does it look like?".)

- In HTML, for example, the < h1 > element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page."

---

# WIREFRAMING

Wireframing is a practice used by UX designers which allows them to define and plan the information hierarchy of their design for a website, app, or product. This process focuses on how the designer or client wants the user to process information on a site, based on the user research already performed by the UX design team.

When designing for the screen you need to know where all the information is going to go in plain black and white diagrams before building anything with code—whether that’s a developer coding it, or you the designer. Wireframing is also a great way of getting to know how a user interacts with your interface, through the positioning of buttons and menus on the diagrams.

Without the distractions of colors, typeface choices or text, wireframing lets you plan the layout and interaction of your interface. A commonly-used argument for wireframing is that if a user doesn’t know where to go on a plain hand-drawn diagram of your site page, then it is irrelevant what colors or fancy text eventually get used. A button or call to action needs to be clear to the user even it’s not brightly colored and flashing.