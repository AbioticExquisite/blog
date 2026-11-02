# 4A. The Dom Tree
Ever wondered how family trees worked? <br>
Here, not only will you figure out how they work, but you will find out through the Document Object Model (DOM) Tree!

So first, you *always* start with window. This is the top-level object: the browser tab. Everything lives inside this. In family terms, he's like the great-great-great-great... many great grandfather.

Next, you have the document. This holds everything of HTML, and is a property of window--the loaded page. Within the document is html, head, body, etc. We'll get into that later in this **document**. See what I did there? Heh.

Anywho, after the document is html, then the head and body. They're siblings with their parent being html. These two tags divide the page into two primary sections. The head is what you don't see on the page: the title, meta, and the other stuff that you find in html:5. The body is what you find on the page: lists, paragraphs, headings, etc. Those elements are the children of head and body (direct parent), and html is their grandparent.