# tracy-beginner-portfolio

You will be learning the basics of html and css. These are like the skeleton and skin of any web app that exists. We can generate them in many ways and create dynamic structures with javascript and other programming langauges. But, generally html and css are the visual component of all web and many antive applications. 

## Start Here

[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)

[HTML & CSS for Beginners Video Course](https://www.youtube.com/playlist?list=PL0eyrZgxdwhwP0AxnbBiDBCi53LK9uCMZ)


With your new found knowledge on html and css you will build the first portfolio attempt. This won't be your final portfolio and isn't expected to be done to a professional level. Rather this is a straight forward portfolio and is intentded to implement some simple principles of web design.

Follow set up and list once you're ready and we'll go through building your web app.

## Set up files

Open a terminal in the root directory of this repo or add a file through your filesystem UI. We want to create an index.html file.

```
touch index.html
```

Now you want to create your other files that will act as your pages. Create an about.html, resume.html portfolio.html, and contact.html.

```
touch about.html portfolio.html contact.html resume.html
```

The other file you need to create to start is your style.css.

```
touch style.css
```

##Connect your files

[]: Create simple html template in each file.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Simple HTML Page</title>
    <link rel="stylesheet" type="text/css" href="./styles.css">
</head>
<body>
    <h1>Welcome to My Simple HTML Page</h1>
    <p>This is an example paragraph to demonstrate the HTML structure.</p>
</body>
</html>
```

[] Edit title of each page to match the name of your file. It can be something different, but for simplicity keep the naming clean.

## Responsive webstites

We need to be making responsive websites in this day and age. A lot of traffic comes from mobile devices now. In fact if you're buildidng international applications, you may see a majority of your traffic in regions is driven by mobile OS. This mean that your layouts need to be flexible and have a solid visual on multiple screen sizes, aka be responsive. Read more about responsive website design here and then complete the readings in the The Grid section following it.

[] Read Tutorial on Responsive CSS
    [Responsive Website Reading](https://www.w3schools.com/css/css_rwd_intro.asp)
    [Responsive Web Design Video](https://www.youtube.com/watch?v=l_zwZoDZoLU)

[] Read Documentation and learn about media queries
    [MDN MNedia Queries Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)

## The Grid

Take some time to understand the grid concept in web design and why we use it. For many webpages, we're not building artisitic implementations of javascript and css that create wild animations, etc. We're usually building the visual interface for a backend application that saves information to a database. The front end is abstracted from this so that we can focuson rendering visuals. This makes a grid system adventageous for building websites in a way that is comfortable and also effective/quick. We get repeatable and predictable design. You will need to choose one of these options to create your grid that your website will be designed in.



### Flexbox
[] Read Docs on Flexbox
    [Flexbox Tutorial](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    [Flexbox Intro and docs](https://www.w3schools.com/css/css3_flexbox.asp)
    [CSS Flexbox Intro | Tutorial for Beginners](https://www.youtube.com/watch?v=B8BFVzbKmPI)

### CSS Grid

[] Read CSS Grid Docs
    [CSS Grid Tutorial](https://css-tricks.com/snippets/css/complete-guide-grid/)
    [CSS Grid Intro](https://www.w3schools.com/css/css_grid.asp)
    [CSS Grid Into and Basics for Beginners](https://www.youtube.com/watch?v=EaWj2AWI5Es)
### Bootstrap

[] Read Documentation on Bootstrap and understand what it is

    [Bootstrap](https://getbootstrap.com/)
    [Bootstrap Intro Video](https://www.youtube.com/watch?v=O_9u1P5YjVc)
    
    Follow Installation instructions here [Bootstrap Quick Start](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

## CSS Excxercises

A fun way to learn your CSS values is through this [CSS EXcercise](https://www.w3schools.com/css/css_exercises.asp) on W3 Schools.

## Front Page

You will create your home poage in your index.html. Follow the checklist and mark off each component as you create it and have it implemented.

[] Page has a nav bar located at the top of the page 
    [Nav Tag](https://www.w3schools.com/tags/tag_nav.asp)
    [Navbar tutorial](https://www.youtube.com/watch?v=f3uCSh6LIY0)
    [] Navigation tabs are added to the right side of the navbar
        [] About
            [] Links to About Page
                [A Tag](https://www.w3schools.com/tags/tag_a.asp)
        [] Resume
            [] Links to Resume
        [] Portfolio
            [] Links to Portfolio
        [] Contact
            [] Links for Contact
[] Centered Title [Header Tag](https://www.w3schools.com/tags/tag_header.asp)
    [] Text is your name
[] Image Centered on page [Image Tag](https://www.w3schools.com/tags/tag_img.asp)
    [] Image is Profesional image of you
[] Social Media links 
    [How To: Social Media Icons/Links](https://www.w3schools.com/howto/howto_css_social_media_buttons.asp)
    [Example of Social Media Icons](https://codepen.io/vishalamipara/pen/ZEYZVvr)
    [] Cnetered Under image
    [] Linked In
    [] Github
    [] other profesional links

## About
[] Navbar
[] Title of Page
[] Professional Pragraph explaining your goals as a developer (Can be Lorem Ipsum) [P Tag](https://www.w3schools.com/tags/tag_p.asp) 

## Portfolio
[] Navbar
[] Grid of Images
    [Grid of Images Example](https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp)
    [How To Grid of Image Video](https://www.youtube.com/watch?v=rnhoY5Cdmy0&t=1s)
    [] Create image grid
    [] Images
        [] Create overlay effect for images
            [Psuedo Elements](https://www.w3schools.com/css/css_pseudo_elements.asp)
            [How TO: Image Overlay](https://www.w3schools.com/howto/howto_css_image_overlay_title.asp)
            [How TO Video: Create Imaage Overlay](https://www.youtube.com/watch?v=SXQ9l0ScDEA)
        [] Image itself is an <a> tag wihtout a destination url
            [A Tag](https://www.w3schools.com/tags/tag_a.asp)
        [] Overlay has generic title

## Contact
[] Navbar
[] Form built with text inputs
    [Input Tag](https://www.w3schools.com/tags/tag_input.asp)
    [Label Tag](https://www.w3schools.com/tags/tag_label.asp)
    [Form Tage](https://www.w3schools.com/tags/tag_form.asp)
    [How to Build a Form](https://www.w3schools.com/howto/howto_css_contact_form.asp)
    [How To Build a Form Video](https://www.youtube.com/watch?v=E5MEzC0prd4&t=1s)
    [] Form allows some one to leave their name, email
        [] Text input email
        [] Text Input Name
    [] Button for Submit
        [Button Tag](https://www.w3schools.com/tags/tag_button.asp)
        [Button Styling]
        [] Button titled Submit

## Resume
[] Navbar
[] This page features a pdf resume embedded in html
    [Embed Tag](https://www.w3schools.com/tags/tag_embed.asp)
    [Iframe](https://www.w3schools.com/tags/tag_iframe.asp)
    [Object Tag](https://www.w3schools.com/tags/tag_object.asp)
    [How to Embed PDF Into HTML Web Page](https://www.geeksforgeeks.org/how-to-embed-pdf-file-using-html/)
    [] Downloadable pdf embedded in page

## CSS Rules

In this challenge write all your css in one file and import that one file into all your html files. Try to re use ids and classes as much as possible from screent to screen. For instance, the navbar at the top of each page should always read the same classes/ids on each screen. In fact you should be able to build the navbar once and copy and paste it into other screens. If you import the same css file, the navbar will be consistent in all of your screens.

## Challenges

## Dynamic Navbbar
In this challenge you will highlight with css the tab that is "active". This means that on the home page all tabs should look the same. However if you click the About link on the navbar, the navbar on the About screen will have a different version of css for the tab. Try to keep your CSS simple and to not create more than one new class/id to acheive this affect. It's certainly possible and you can manage the change page by page in html. Another idea is to create a base class 

## Form Validation
Look into simple form validation with html tags. We won't use this too much, but it can be fun to create styles that are accepted dynamically without a heavy javascript library performing the comparisons.
