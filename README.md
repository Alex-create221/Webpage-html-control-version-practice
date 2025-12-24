# Webpage-html-control-version-practice
in this page I will add all I have learned from udemy´s course and coddy to make html documents


# ver 1.0 

# HTML Head and Text Formatting Practice 

This version is a learning excersice focused on understanding how HTML can
support document metadata and semantic text formatting.

## Concepts I have practiced

This practice has the following HTML concepts:

- Proper use of the '<head>' element
- Defining a descriptive '<title>'
- Linking external resources using '<link>'
- Use of favicons with different formats and sizes for other browsers
- Semantic text tags for quotations, abbreviations, text directions, paragraphs, header and main

  ## HTML tag used

  Are the following:

  - '<head>': Contains metadata such as the document title and external resources
  - '<title>': Defines the name shown in the browser tab
  - '<link>': Used to link favicon files
  - '<blockquote>': Represents a long quotation taken from an external source or webpage. It doesn´t display the quoted text (it has to be added by CSS)
  - '<q>': Define a short inline quotation inside a paragraph. It can display the quoted text by default
  - '<abbr>': Define the abbreviation and it allows the user its full meaning using the 'title' atribute. Generally used for acronyms
  - '<bdo>': Overrides the text direction using the 'dir' atribute and the values 'rtl' and 'ltr'. Generally used for foreing languages like arabic and Hebrew

## What I have learned 

While I was building this web page, I have learned these concepts:

- Favicons must be inside of '<head>' tag, some linked resources need to be added according to MIME type standard to have a well done described resources like image/png  need to be added for files with .png
- Some types are not generally used like Apple touch
- '<blockquotes>' define long independent quotations used apart from other paragraphs, while '<q>' define short inline quotes used inside other paragraphs, in this tag do not break the text flow and display the quoted tex by default
- The '<abbr>' define semantic meaning, accesibility and better SEO position
-  HTML defines the meaning and the structure of web content and is the most basic building block of the web. Responsible of put images, text, and other type of content to display in a Web Browser. Using elements known as "tags" which consist of the element name surrounded by < > (angle brackets) that are capable of changing the format text, including images, links, and other functions.
-  Using semantic tags is better than using div tag for meaning semantic text.


## Conslusion

I have learned many tags to include favicons, resources, and some tags that can change the text format. allowing me to know HTML is a markup language that is capable of creating the blocks (structure) needed to create and display the content in a webpage, this is not capable of making desing or changing any style, is just responsible for building the skeleton that later will be added with some style using CSS. Using the Head tag, I realized That is responsible of describing the HTML document adding some value information content and resources. It contains the machine readable information (metadata) about the document. It holds information for machine processing, not for users readability, for human readability use the header tag instead.
The other tags like blockquotes, q, abbr and bdo tags are responsible for change the format of the text giving more precise information and creating the flow of the text with other semantic tags like header, main of footer inside the body tag. 
