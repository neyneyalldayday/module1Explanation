GIVEN a webpage meets accessibility standards
**this just means a webpage works for everyone, people with no eyes or no ears or shitty 3rd world internet or a 40 year old computer



WHEN I view the source code
** when a grader looks at your repository
THEN I find semantic HTML elements
**semantinc html elements are able to be read aloud with
the use of a screen reader. for those people with no eyes
#mainly :
<main></main> **this would wrap the main chunk of content

<section></section> **a smaller <div></div> with content in it think a div with divs in it.

<article></article> ** a paragraph or sentence

<aside></aside> ** for vertical side content like an ad on the side of a page.

<nav></nav> **navbars

<footer></footer>  ** for like an opposite navbar at the bottom kinda thing

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

** do you have parent elements that contain
child elements  with elements inside it.

**does this
<section>
**wrap this
    <article>
    *that holds these
        <h1>some shit</h1>
         <p>
          The quick brown fox jumps over the lazy dog, showcasing its agility and speed in a remarkable display of natural prowess
          </p>
    </article>
</section>

**mainly you dont have to worry about this for this assignment idk why its there.

WHEN I view the icon and image elements
THEN I find accessible alt attributes

*images have attributes inside the <img> tag.


*mainly src which points to where the image lives in your file structure

*but then there is another one called alt this is for
those no eye having people again. this explains whats pictured in the image.

*ex
<img src="./somewhere/onMy/computer" alt="some image of a cat">

WHEN I view the heading attributes
THEN they fall in sequential order

this is referring to the "h" elements 
<h1></h1><h2></h2>
etc.

code is read from top to bottom. as the page flows downward the heading number increases. you wouldnt have an h1 at the bottom of the page. 

*top of the page
<h1></h1>



somewhere lower
<h2></h2>






even lower

<h3></h3>



so on

WHEN I view the title element
THEN I find a concise, descriptive title

again thats just <title>A really Good title</title>