# webby-site
This is a basic website template, with simple HTML and CSS docs using css-grid. I've also included a `media` folder as an example of how to link to any files you may want to store in a subfolder of your website. I use this to make my own websites, and I encourage you to, as well!

## How to use this template

There are two main files in this project: index.html and webby.css. 

### index.html

**index.html** is the front page of your website, and it's what people will automatically see when they visit your site. In our example, when people visit `webbysite.com`, they'll see the index.html file. 
   - Keep in mind that if you change the name of the base `index.html` file, it will no longer be shown automatically as the front page of your website.

### webby.css
**webby.css** is the main css file for the site. 

You are free to rename the .css file, but make sure you also update index.html to include the new name instead of webby.css. 

If the css on your page is not working, make sure that you're telling the computer the right place to find it: if your page is in a different folder, for example, you'll need to tell the computer which folder to find the css file in. 

The CSS doc in this template has different elements set as specific colors to help you visualize how the CSS works and how the parts on your site are moving around as you edit them, and so they aren't exactly meant to be beautiful. I encourage you to change these colors to be whatever you want!

### adding new pages

You can add additional pages to your site as desired. I do this by copying `index.html` into a new file and editing it as necessary. 

**Note** that you don't have to include '.html' in the file name as long as you include the `<!DOCTYPE` bit at the top of the document. Whatever you name the file, that's what its URL will be: so a file named `page.html` will show up at `webbysite.com/page.html`, and a page named `example` will show up at `webbysite.com/example`. However, keep in mind that if you change the name of the base `index.html` file, it will no longer be the automatic front page of your website.

## a note on code comments

HTML and CSS both have code comments, which allow you to write notes in your document that won't be read as code. I've put some comments in these files to help explain how the template works, but you should feel free to remove them if you don't need them. You can also (obviously, I guess) add your own comments.

In HTML, a code comment is formatted as follows:
````
<!-- this is a note! -->
````

In CSS, a code comment is formatted as follows:
````
/* css code comment */
````

