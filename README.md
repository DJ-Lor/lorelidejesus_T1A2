# LoreliDeJesus_T1A2 - Portfolio Website #
___
* Published Portfolio: [INSERT LINK](https://www.example.com)
* GitHub Repo: [INSERT LINK](https://www.example.com)
* Presentation Deck: [INSERT LINK](https://www.example.com)

___
## Table of Contents ##
1. Purpose
2. Target Audience
3. Functionality and Features
4. Sitemap
5. Wireframes
6. Tech Stack
___

## 1. Purpose ##

I am an aspiring developer aiming to showcase my coding experience and abilities through this online portfolio. 

The overall goal is to receive a job offer and/or an offer to collaborate with other peers in support for continued learning. 

___
## 2. Target Audience ##

**Primary:** This portfolio is created for prospective future employers looking to engage a developer. 

**Secondary:** Peers in the industry looking to collaborate on future projects together. 

___

## 3. Functionalities and Feature ##

1. HTML 

* Started creating the header, meta data, links to CSS stylesheets, the main and the footer to build the baseline skeleton of the website. 

* The header contains a logo and a navigation. 

* The logo directs the user back to the index page. 


```html

 <header>
        <div class="header-left-content">
            <div class="my-logo">
                <a href="/"><img src="/images/my-logo.png" class="my-logo" alt="my-logo"></a>
            </div>
        </div>
        <div class="header-right-content">
            <nav class="header-nav-list">
                <a class="nav-list active" href="/about.html">About</a>
                <a class="nav-list" href="/blog.html">Blog</a>
                <a class="nav-list" href="/contact.html">Contact</a>
            </nav>
        </div>
    </header>
````
* The footer contains links to social media and contact details. A script is included on the HTML head for the icons to reflect. 

```html
  <script src="https://use.fontawesome.com/abf61f5ec6.js"></script>
```

```html
    <footer class="footer-blog">
        <div class="social-media-blog">
            <div class="mini-circle-blog">
                <a href="https://www.linkedin.com/feed/" class="mini-circle-a-blog" target="_blank"><i class="fa fa-linkedin"
                        aria-hidden="true"></i></a>
            </div>
            <div class="mini-circle-blog">
                <a href="https://github.com/DJ-Lor" class="mini-circle-a-blog" target="_blank"><i class="fa fa-github"
                        aria-hidden="true"></i></a>
            </div>
            <div class="mini-circle-blog">
                <a href="tel:+61410301987" class="mini-circle-a-blog" target="_blank"><i class="fa fa-phone"
                        aria-hidden="true"></i></a>
            </div>
            <div class="mini-circle-blog">
                <a href="mailto:dejesus.loreli@gmail.com" class="mini-circle-a-blog" target="_blank"><i class="fa fa-envelope"
                        aria-hidden="true"></i></a>
            </div>
            <div class="line-blog"></div>
        </div>
    </footer>
```

* Call-to-Action buttons are placed in key pages to promote target audience engagement. 
    * index.html
    * about.html
    * contact.html

* Images are present on key pages to complement text-heavy pages and keep the target audience attention.  


2. CSS

* Utilised a mobile-first approach strategy in building a responsive website. 

* Defined the primary and secondary colors and added this to all text and background colors. 
    * #F5E2C8
    * #6D1A36
    * #230C0F

* Defined the official website font through google fonts (https://fonts.google.com/specimen/Montserrat) and font family established. Also set the global styling to a blank canvas.

```css
* {
    padding: 0;
    margin: 0;
    border: none;
    box-sizing: border-box;
    font-family: "Montserrat", serif;
    text-decoration: none;
}
```
* Navigation bar a tag text are styled to change colors when hovered over. This also remains highlighted in color when the user is active and on page. This is for the user to easily understand where they are in the navigation user journey. 

![Nav-bar](/images/nav-bar.png)

* Call-to-Action button styling included a drop-down shadow for a embossed effect. 

![Button](/images/button-1.png)

* The footer includes links to the social media and contact information. This is present across all the website to complement the Contact-page and also to make it easy for the user to contact the developer at any point in their user journey. This footer is styled vertically in desktop and horizontally in smaller devices. 

* The footer icons are from fontawesome.com and have been styled to adjust sizing and color to fit for this website. 

![Footer-desktop](/images/footer-desktop.png)
![Footer-mobile](/images/footer-mobile.png)

___

## 4. Sitemap ##

* pages/
    * index.html
    * about-me.html
    * blog.html
    * blogs/
        * blogs-1.html
        * blogs-2.html
        * blogs-3.html
        * blogs-4.html
        * blogs-5.html
        * blogs-6.html
    * contact.html
* css/
    * styles.css
* images/
        * ...
* docs/
        * ...
* .gitignore

___

## 5. Wireframes ##

![Root](/images/wireframe-root.png)
![About-page](/images/wireframe-about-page.png)
![Blog-page](/images/wireframe-blog-page.png)
![Blog-article-page](/images/wireframe-blog-article-page.png)
![Contact-page](/images/wireframe-contact-page.png)

___

## 6. Tech Stack ##

* html
* css
* google fonts
* fontawesome
* netlify

