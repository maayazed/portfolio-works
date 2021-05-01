<!DOCTYPE html>
<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" style="text/css" href="./assets/css/style.css">
    <title>Contact Landing Page Draft</title>
    <!--Project 1:  the parameters for this page is to draft a HTML markup from scratch using semantic markup, and CSS layout
limited to padding, border, margin, display, and positioning only to achieve a contact landing page.-->

<!--HTML guide: 
    <article>	Defines independent, self-contained content
    <aside>	Defines content aside from the page content
    <details>	Defines additional details that the user can view or hide
    <figcaption>	Defines a caption for a <figure> element
    <figure>	Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.
    <footer>	Defines a footer for a document or section
    <header>	Specifies a header for a document or section
    <main>	Specifies the main content of a document
    <mark>	Defines marked/highlighted text
    <nav>	Defines navigation links
    <section>	Defines a section in a document
    <summary>	Defines a visible heading for a <details> element
    <time>	Defines a date/time-->

<!--CSS guide:
    {display: none;}
    {display: inline;}
    {display: block;}
    {position: static;} not affected by the top, bottom, left, and right properties
    {position: relative;} setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left
    {position: absolute;} is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed)
    {position: fixed;} is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element-->
</head>
 
<body>
    <header> 
        <section> 
            <nav>
            <ul>
                <li><span class>Landing Page</span></li>
                <li>Contacts:</li>
                <li>Github</li>
                <li>Portfolio</li>
                <li>Email</li>            
            </ul>
            </nav>
        </section>
    </header>

    <main>
        <section>
            <h1 class="text-center">Main Page</h1>
            <p class="text-center">Refer to the text below</p>
            <br>
            <figure>Home</figure>
            <article class="text-left">
                <h3>Personal Information Input</h3>
                <form>  
                    <ul>
                        <li>
                    <label>Name:</label>
                        <input type="text" id="name" name="user-name">
                        </li>
                        <li>
                    <label>Email:</label>
                        <input type="text" id="email" name="user-email">
                        </li>
                    </ul>
                    <button type="submit">Enter</button>
                </form>    
            </article>    
        </section>
    </main>
    
    <footer>
        <h5>Page Links</h5>
    </footer>
</body>

</html>