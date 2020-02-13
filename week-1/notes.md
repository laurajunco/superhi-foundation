# Week 1

## 1. What is the World Wide Web?

- All websites are made using only 3 front-end languages: HTML, CSS and JavaScript

- 1989 the World Wide Web was created by Tim Berners Lee: an open platform to be able to share information easily and locate it from anywhere

The web is made up of three key things:

1. **HTML**: describes content and its nature
2. **URLs**: address to uniquely identify websites and files on the web
3. **HTTP**: communication between server and client. 

-  The internet existed before the web, It has been around since the 60s. Includes: emails, the web, apps, the cloud, internet of things. 


#### Making websites:

- **HTML**: describes the content on a website. 
- **CSS**: describes how content should look on the page

- All html content is organized into boxes

## 2. Writing our first HTML

HTML is made up of 4 things

1. **Tags**: < h1 > has an opening and a closing tag < / h1 >
2. **Content**: < h1 > contents inside tags < / h1 >
3. **Comments**: text inside code that wont display on the browser
4. **Attributes**: describe certain parts of the page with a bit of more information. the go in the opening tag.

- There are about 100 tags (for all kinds of content) but usually you use about 15.

- **img tag** is a self closing tag!

## 3. Writing our first CSS

CSS grabs elements from a page and allows us to apply styles to them

1. selector: p {}
2. css rules: name of rule (property): value;

p {
    color: #ff083;
}

## 4. Sally Hart Photography

- **Header tag** < header >: a container for introductory content or navigational links

- **Section tag** < section >: defines sections in a document. 

- The background image will be added with CSS

- **href="mailto:"**: opens up email client installed on pc or phone

-**href="tel:"**: opens phone app to call that number

- **background-image**: receives url of image

**background-size**
- auto = shows image original size
- cover =  image covers the entire container without skewing or repeating the image
- contain = image is always fully visible

**vh**: viewport height, relative to the height of browser window

**vw**: viewport width.

These are ways to link the size of viewport to the size of the page elements

**position: fixed**: precisely positions elements in relation to browser viewport. These elements are in an independant layer on the screen.

- top, left, bottom, and right: allmost always go hand in hand with position: fixed;

- general styles in the < body > tag get applied to all elements. It is needed to go to the specific element and override those styles

- pseudoselector: a:hover

**classes** a class name allows to select several items on the apge and apply styles to them

**How does ccs know when to apply rules or override styles??**

1. Reads css file from top to bottom. last thing on the css is the last thing applied to the page

2. With classes you can single out elements

**background-attachment**: fixed; = parallax effect, fixes the background to the browser viewport rather than to the section


## 5. Homework: the pen is mightier than the sword

**Scalable Vector Graphics**: SVG stands for scalable vector graphics which means they don’t pixelate when really large. Typically transparent in background so you can change the color of the background when styling in CSS.

- svg can be added using the < img > tag or the background-img css property