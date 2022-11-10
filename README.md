# LoreliDeJesus_T1A2 - Portfolio Website #
___
* Published Portfolio: [https://loreli.netlify.app/](https://loreli.netlify.app/)
* GitHub Repo: [https://github.com/DJ-Lor/lorelidejesus_T1A2](hhttps://github.com/DJ-Lor/lorelidejesus_T1A2)
* Presentation Deck: [https://youtu.be/NFFaK-HktKE](https://youtu.be/NFFaK-HktKE)

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

* The logo directs the user back to the index page. Logo was also utilised for favicon across all pages. 


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
* The footer contains links to social media and contact details. A [Fontawesome](https://fontawesome.com/) script is included on the HTML head for the icons to reflect.  

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

* Images are present on key pages to complement text-heavy pages and keep the target audience attention. Utilised [Unsplash](https://unsplash.com/) for free, no copyright images. 

2. CSS

* Utilised a mobile-first approach strategy in building a responsive website. 

* Defined the primary and secondary colors and added this to all text and background colors. 
    * #F5E2C8
    * #6D1A36
    * #230C0F
    * #F4FDAF

* Defined the official website font through [google fonts](https://fonts.google.com/specimen/Montserrat) and font family established. Also set the global styling to a blank canvas. 

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

![Nav-bar](/docs/nav-bar.png)

* Call-to-Action button styling included a drop-down shadow for a embossed effect. 

![Button](/docs/button-1.png)

* The footer includes links to the social media and contact information. This is present across all the website to complement the Contact-page and also to make it easy for the user to contact the developer at any point in their user journey. This footer is styled vertically in desktop and horizontally in smaller devices. 

* The footer icons are from fontawesome.com and have been styled to adjust sizing and color to fit for this website. 

![Footer-desktop](/docs/footer-desktop.png)
![Footer-mobile](/docs/footer-mobile.png)

* Once the website structure and style was complete, I then added two key animations to strike a stronger first impression:

    * Logo Zoom In Hover (Desktop)
    * Landing Page Body Slide from Left Animations (All Viewports)
___

## 4. Sitemap ##

![Sitemap](/docs/sitemap.png)

___

## 5. Wireframes/Mock Ups ##

Utilised [Figma](https://www.figma.com/) to create the website's wireframe/Mock up. 

1. Landing Page 
 * Wireframe/Mock Up

![Root](/docs/wireframe-root.png)

 * Published Version

 ![Published-LP](/docs/published-landing-page.png)

 2. About Page
 * Wireframe/Mock Up

![About-page](/docs/wireframe-about-page.png)

 * Published Version

 ![Published-About-page](/docs/published-about-page.png)

3. Blog Page
 * Wireframe/Mock Up

![Blog-page](/docs/wireframe-blog-page.png)

 * Published Version

![Published-Blog-page](/docs/published-blog-page.png)

4. Blog Article Page 
 * Wireframe/Mock Up

![Blog-article-page](/docs/wireframe-blog-article-page.png)

 * Published Version

![Published-Blog-article-page](/docs/published-blog-article-page.png)

5. Contact Page
 * Wireframe/Mock Up

![Contact-page](/docs/wireframe-contact-page.png)

 * Published Version

 ![Published-Contact-page](/docs/published-contact-page.png)
___

## 6. Tech Stack ##

* [HTML](https://www.w3schools.com/html/html_intro.asp)
* [CSS](https://www.w3schools.com/css/css_intro.asp)
* [Google Fonts](https://fonts.google.com/)
* [Fontawesome](https://fontawesome.com/)
* [Netlify](https://www.netlify.com/)

____

## References ## 

* Banks, C. (2019). We are better when we are united [Image].  Retrieved 24th of October 2022 from https://unsplash.com/photos/LjqARJaJotc
* Figma (n.d.). Wireframe Screenshot Reference. 
* Google (n.d.). Montserrat font reference. Retrieved 24th of October 2022 from https://fonts.google.com/specimen/Montserrat
* Heyerlein, H. (2017). Person with assorted color paint on face photo [Image]. Retrieved 24th of October 2022 from https://unsplash.com/photos/ndja2LJ4IcM 
* Lanre-Ologun, D. (2018). Coding together, featured in Editorial, Business & Work, Technology [Image]. Retrieved 24th of October 2022 from https://unsplash.com/photos/kwzWjTnDPLk 
* Mesh, C. (2020). Close up picture of a keyboard [Image].  Retrieved 24th of October 2022 from https://unsplash.com/photos/X0z-meKcGAE
* Schneider, C. (2020). Plexus Net [Image].  Retrieved 24th of October 2022 from https://unsplash.com/photos/xuTJZ7uD7PI
* Spiske, M.  (2020). Web source code java script. Made with analog vintage lens, Leica * Summicron-R 2.0 35mm (Year: 1978) [Image].  Retrieved 24th of October 2022 from https://unsplash.com/photos/hbb6GkG6p9M
* Unsplash (n.d.). Github Icon. Retrieved 24th of October 2022 from  https://fontawesome.com/v4/icon/github
* Unsplash (n.d.). Phone Icon. Retrieved 24th of October 2022 from  https://fontawesome.com/v4/icon/phone
* Unsplash (n.d.). Linkedin Icon. Retrieved 24th of October 2022 from  https://fontawesome.com/v4/icon/linkedin
* W3Schools (n.d.) Reference to CSS and HTML codes from https://www.w3schools.com/
