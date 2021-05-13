# The Document Object Model (DOM)
## DOM stands for Document Object Model, a representation of an HTML document in nodes and objects. Browsers expose an API that you can use to interact with the DOM. This is how modern JavaScript frameworks work - they use the DOM API to tell the browser what to display on the page. <br>
#### <br> The DOM is the browser’s internal representation of a web page. When the browser retrieves your HTML from your server, the parser analyzes the structure of your code and creates a model of it. Based on this model, the browser then renders the page on the screen.
#### <br> Browsers expose an API that you can use to interact with the DOM. This is how modern JavaScript frameworks work - they use the DOM API to tell the browser what to display on the page.
#### <br> In Single Page Applications, the DOM continuously changes to reflect what appears on the screen, and as a developer you can inspect it using the Browser Developer Tools.
#### <br> The DOM is language-agnostic, and the de-facto standard to access the DOM is by using JavaScript, since it’s the only language that browsers can run.

#### <br> *The DOM is standardized by WHATWG in the DOM Living Standard Spec.*

#### <br> JavaScript can interact with the DOM to:

* #### inspect the page structure
* #### access the page metadata and headers
* #### edit the CSS styling
* #### attach or remove event listeners
* #### edit any node in the page
* #### change any node attribute

#### The main 2 objects provided by the DOM API that you you will interact the most with are **document** and **window**.

# The Window object :-
#### The **window** object represents the window that contains the DOM document.

#### <br> **window.document** points to the **document** object loaded in the window.

#### <br> Properties and methods of this object can be called without referencing **window** explicitly, because it represents the global object. So, the previous property **window.document** is usually called just **document**.

# The Document object
### The **document** object represents the DOM tree loaded in a window.

#### Here is a representation of a portion of the DOM pointing to the head and body tags:

<p align="center">
<img src="https://flaviocopes.com/dom/dom-body-head.png" width="500" height="500" border="10"/>
</p>


#### <br> The Document object can be accessed from window.document, and since window is the global object, you can use the shortcut document object directly from the browser console, or in your JavaScript code.

## Most used API methods :-

* #### document.getElementById()
* #### document.querySelector()
* #### document.querySelectorAll()
* #### document.getElementsByTagName()
* #### document.getElementsByClassName()

#### we can get the document title using **document.title**, and the URL using **document.URL**. The referrer is available in **document.referrer**, the domain in **document.domain**.

### From the **document** object we can get the body and head Element nodes
* #### document.documentElement: the Document node
* #### document.body: the body Element node
* #### document.head: the head Element node

#### We can also get a list of all the element nodes of a particular type, like an HTMLCollection of all the links using **document.links**, all the images using **document.images**, all the forms using **document.forms**.

#### The document cookies are accessible in **document.cookie**. The last modified date in **document.lastModified**.

#### You can do much more, even get old school and fill your scripts with document.write(), a method that was used a lot back in the early days of JavaScript to interact with the pages.

# Reference:-
#### [flaviocopes.com (https://github.com/lifeparticle/The-Ultimate-Markdown-Cheat-Sheet)
