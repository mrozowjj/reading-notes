# Code 201 Reading Assigment 3

## Learn HTML

### Creating Hyperlinks

1. To create a basic link, we wrap text or other content inside what element?

An \<a href="link">Text\</a>

Where the website link is the link and the text is the text that will become a hyperlink.

2. The href attribute contains what information?



3. What are some ways we can ensure links on our pages are accessible to all readers?

The following is copied direct from the reading:
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks


* Screen reader users like jumping around from link to link on the page, and reading links out of context.
* Search engines use link text to index target files, so it is a good idea to include keywords in your link text to effectively describe what is being linked to.
* Visual readers skim over the page rather than reading every word, and their eyes will be drawn to page features that stand out, like links. They will find descriptive link text useful.
* Don't repeat the URL as part of the link text — URLs look ugly, and sound even uglier when a screen reader reads them out letter by letter.
* Don't say "link" or "links to" in the link text — it's just noise. Screen readers tell people there's a link. Visual users will also know there's a link, because links are generally styled in a different color and underlined (this convention generally shouldn't be broken, as users are used to it).
* Keep your link text as short as possible — this is helpful because screen readers need to interpret the entire link text.
* Minimize instances where multiple copies of the same text are linked to different places. This can cause problems for screen reader users, if there's a list of links out of context that are labeled "click here", "click here", "click here".



## CSS Layout

### CSS Layout: Normal Flow CSS Layout: Positioning

1. What is meant by “normal flow”?

Normal flow is what a webpage does when you don't chage their layout. i.e it's the default way a page would display if you didn't to any CSS to the page at all.

2. What are a few differences between block-level and inline elements?

Block level elements fill the available space of the parent element where inline is the size of the content period.

3. ___ positioning is the default for every html element.

Static

4. Name a few advantages to using absolute positioning on an element.

With absolute the object will be in the same locations relative to it's nearest positioned ancestor element.

5. What is a key difference between fixed positioning and absolute positioning?

Fixed is almost exactly the same as absolute but it is relative to the visible portion of the viewport which is useful if you want to creat a persistent navigation menu that is always in the same spot on the page no matter how much you scroll

## Learn JS

### Functions – Reusable Blocks of Code

1. Describe the difference between a function declaration and a function invocation.

The function declaration is like the assignment of a variable; without the declaration the function does not exist and it only needs to happen once. The invocation is the function being called or executed and can happen as many times as you need.

2. What is the difference between a parameter and an argument?

There isn't one; with functions parameters are sometimes called arguements interchangably.

## Miscellaneous

### 6 Reasons for Pair Programming

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.

Greater efficiency - it's easier to spot mistakes with two people looking at the same code.

Engaged collaboration - it forces you to focus on the code and not get distracted.