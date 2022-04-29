[![My Skills](https://skillicons.dev/icons?i=html)](https://skillicons.dev) 
## About HTML 📜
`H`yper `T`ext `M`arkup `L`anguage

HTML is the standard markup language for Web pages and describes the structure of a Web page. 
The structure is built with different elements to tell the browser how to display the content.

**HTML was created by Sir Tim Berners-Lee in late 1991 but was not officially released.**

1995: HTML 2.0 was published

1999: HTML 4.01 was published - *(Major Version of HTML)*

2012: HTML5 was published

- HTML 1.0 was released in 1993 with the intention of sharing information that can be readable and accessible via web browsers. But not many of the developers were involved in creating websites. So the language was also not growing.

- Then comes HTML 2.0, published in 1995, which contains all the features of HTML 1.0 along with that few additional features, which remained as the standard markup language for designing and creating websites until January 1997 and refined various core features of HTML.

- Then comes HTML 3.0, where Dave Raggett introduced a fresh paper or draft on HTML. It included improved new features of HTML, giving more powerful characteristics for webmasters in designing web pages. But these powerful features of the new HTML slowed down the browser in applying further improvements.

-  Then comes HTML 4.01, which is widely used and was a successful version of HTML before HTML 5.0, which is currently released and used worldwide. HTML 5 can be said for an extended version of HTML 4.01, which was published in the year 2012.

*[W3Schools, HTML History Document](https://www.w3schools.in/html/history)*

## Links 🔗
Useful websites for learning:
| Name | Website |
| ------ | ------ |
| HTML Living Standard Docs | [w3.org](https://html.spec.whatwg.org/) |
| HTML Tutorial | [w3schools.com](https://www.w3schools.com/html/default.asp) |
| MDN Web Docs | [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/HTML) |
| Wiki Self-HTML (German) | [wiki.selfhtml.org](https://wiki.selfhtml.org/wiki/HTML)  🇩🇪 |
| Mediaevent HTML (German)| [mediaevent.de](https://www.mediaevent.de/html/) 🇩🇪 |

## HTML Basics 💻

__First Things First - The Golden Rules__
> Focus on the basics and only learn advanced things when you need them. <br> 
> Otherwise, it can quickly become overwhelming and you lose your focus on studying. <br>
> Skipping basic knowledge is never a good idea, even it is much more time-consuming. <br>
> Every little advance means that you have learned something new, and this knowledge is a great benefit later on.

In this section I'll cover the basic elements of HTML, which we also call skeleton. Mostly these elements are used in web projects. There are a variety of HTML tags, usually you never need all of these tags and elements in a single website project. However, there are HTML tags and elements that are used very often and it is important to focus on them in the beginning.

I think the basics also include *Semantic HTML Elements* <br>
These are important elements to build a good structure and they are also optimized for SEO (Search Engine Optimization). Of course, search engines like: Google don't need Semantic HTML Elements to understand what your website is about. But understanding how Semantic HTML Elements work and how to use them correctly can be a great advantage.

Once you have learned and understood the basics, you will quickly notice that larger websites use many different HTML tags and elements in the `<head>` especially the `<meta>` tags are important, but these are advanced topics. However, the HTML elements inside the `<body>` are often the same to create a web page.

## HTML Folders & Files 🗃️ 

Use only lower case letters, digits & underscores
- No SPACES or TABS, No COMMAS or APOSTROPHES, No SLASHES or QUOTES 
- No `#` `&` `%` `+` `*` `=` `@` `~` `^` `$` `< >` `( )` `[ ]` `{ }` `:` `;` `?` `!`
- No other unusual characters

The file name should be no more than 32 characters, including the file suffix <br>
Examples: *filename.html , filename.css , filename.js* <br>
Because your filename will become part of your Web page's URL.

#### Basic Folder Structure 📁
  1. root (webproject name)
  2. styles
  3. scripts
  4. images
  
  Example of a simple folder structure:
  ```sh
  ├── projectname [root_folder]
  │   ├── index.html
  │   ├── blog.html
  │   ├── styles 
  │   │   ├── style.css
  │   │   ├── style-blog.css
  │   ├── scripts 
  │   │   ├── main.js
  │   │   ├── animation.js 
  │   ├── images
  │   │   ├── background.img
  │   │   ├── blog-article.img
  ```
Note: *The folder structure depends on the individual project. It is important to create a root directory with the project name. All files and subfolders are stored in this root directory. The subfolders can also contain files.*
  
## HTML Tags & Elements ⚙️

- HTML Tags are the keywords

- An HTML element is defined by a `<start tag>` ...some content... `</end tag>`

- The HTML element is everything from the `<start tag>` to the `</end tag>`

- Some HTML elements have no content, for example the `<br>` element. <br>
  These elements are called empty elements. Empty elements do not have an `</end tag>`

### Basic HTML Code
```sh
<!DOCTYPE html>
<html lang="en">
<head>
  <title>My first Website</title>
</head>
<body>
  <h1>Hello HTML</h1>
</body>
</html>
```
![hellohtml](https://user-images.githubusercontent.com/92650697/165988710-edd65c7d-add0-4abd-a76c-e9ee7429269c.png)

This is the first, very simple HTML document. These elements can already be displayed by the browser because the browser understands it is an HTML document. The web page displays the heading 'Hello HTML' to the visitors.

In order to understand why only the `<h1> Hello HTML </h1>` element is visible, we need to understand the different HTML tags and elements in detail and how the web browser interprets, reads and uses them.

## !DOCTYPE
`<!DOCTYPE html>`

All HTML documents must begin with a declaration. The declaration is not an HTML tag. It is "information" for the browser about what type of document it is expecting. Basically, only the html declaration is used for modern websites. 

Note: `<!DOCTYPE html>` is an empty element.

## html
`<html> ... </html>`

This is the root of every HTML Document and it is the container of all other HTML elements. *Except for the `<!DOCTYPE>` tag* <br>
We wrap our `<head>` and `<body>` using the `<html> ... </html>` element. That's why an `</html>` end tag is always at the end of every HTML document. We need it to hold our head and body together.

Note: Always include the lang attribute inside the `<html>` tag, to declare the language of the Web page. This is important so that search engines can understand what language is used for the website. For example: English. `<html lang="en"> ... </html>`

## head
`<head> ... </head>`

The head stores all important data about our website. The element contains any metadata and is always above the `<body> ... </body>` element. Metadata is not displayed, it is processed in the background and usually defines the document title, character set, styles, scripts and other meta information.

## body
`<body> ... </body>`

The `<body> ` tag defines everything that is visible in the web browser. It is the main container and contains all the important content for a website project. For example: headings, paragraphs, images, hyperlinks, tables, lists, etc.

Note: There can only be one `<body> ... </body>` element in an HTML document.
