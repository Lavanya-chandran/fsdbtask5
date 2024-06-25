WINDOW:
Window is the main JavaScript object root, aka the global object in a browser, also can be treated as the root of the document object model. You can access it as window.
Well, the window is the first thing that gets loaded into the browser. This window object has the majority of the properties like length, innerWidth, innerHeight, name, if it has been closed, its parents, and more.

DOCUMENT:
What about the document object then? The Document object(DOM) is your html, aspx, php, or other document that will be loaded into the browser. The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc. What does this really mean? That means if you want to access a property for the window it is window.property, if it is document it is window.document.property which is also available in short as document.property.

window.document or just document is the main object of the potentially visible (or better yet: rendered) document object model/DOM.

Since window is the global object you can reference any properties of it with just the property name - so you do not have to write down window. - it will be figured out by the runtime.

SCREEN:
The Window object also has a screen object with properties describing the physical display:
screen properties width and height are the full screen
screen properties availWidth and availHeight omit the toolbar
window.screen or just screen is a small information object about physical screen dimensions.