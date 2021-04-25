# challenge-1
To refactor existing webpage to make it accessible so site is optimized for search engines.

Acceptance criteria for the webpage:
- Meets accessibility standards
- Applies semantic HTML elements
- Elements follow a logical structure independent of styling and positioning
- Includes accessible alt attributes in images
- Heading attributes fall in sequential order
- Includes a concise, descriptive title element

Additional requirements for webpage:
- Ensure all links are functioning correctly
- Clean up the CSS selectors and properties to make it efficient
- Organize and consolidate application's CSS selectors and properties to follow semantic structure
- Application's CSS file is properly commented


## The Process
To accomplish this challege, these were the steps:
- Understanding the webpage purpose and content to get a clear idea of the project
- Researching to understand the following key concepts
  - What is code refactoring
  - Semantic HTML
  - Web accesibility standards
  - How to make a clean code
  - What README.mb file are for
- Then apply above concepts in the editing of the HTML and CSS files

\
Modifications to the HTML file
'''
Description comments were added for organization

<!--header-->
<!--end header-->

<!--main image-->

<!--content-->
<!--end of content-->

<!--benefits-->

<!--footer-->

Added empty lines to make HTML more organized

Changed title to "Digital Marketing Strategies Homepage"

Changed <div> to <header> tag

HTML: Changed <div> to <nav> in the <header> CSS: Changed .header to .header nav

Changed the main image <div> to <section>

Changed <div> in content section to <main>

Changed <div> in benefits section to <aside>

Added <footer> to footer section 

Included alt propers with relatable desription for all images

\
Modifications to the CSS file
'''
Description comments were added for organization, css rules were consolidated, and organized in order to provide clearance in cascading rules application. 

/* - - - - - header - - - - - */

/* - - - - - main image - - - - - */

/* - - - - - content - - - - - */

/* - - - - - benefits - - - - - */

/* - - - - - footer - - - - - */

No findings of CSS rules that could be simplified or deleted. 

Rules that were simplified into one rule: 

.search-engine-optimization, 
.online-reputation-management, 
.social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

.search-engine-optimization img, 
.online-reputation-management img, 
.social-media-marketing img {
    max-height: 200px;
}

.benefit-lead,
.benefit-cost,
.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
    }


.benefit-lead h3,
.benefit-cost h3,
.benefit-brand h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-brand img,
.benefit-cost img,
.benefit-lead img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

## The Output
We were able to ensure accessible standards through research, specfic changes to both HTML and CSS files, and application of concepts. 

challenge-1 was upload to [Github](https://github.com/) at the following repository: 
[https://github.com/brieeikeseth/challenge-1](https://github.com/brieeikeseth/challenge-1)

Access to deploted application in GitHub:
[https://brieeikeseth.github.io/challenge-1/](https://brieeikeseth.github.io/challenge-1/)

## References 

[What is code refactoring](https://www.altexsoft.com/blog/engineering/code-refactoring-best-practices-when-and-when-not-to-do-it/)

[Semantic Html](https://www.w3schools.com/html/html5_semantic_elements.asp)

[Web Accesibility Standards](https://www.youtube.com/watch?v=-ao_Kc_8rpE)

[How to write clean code](https://www.geeksforgeeks.org/7-tips-to-write-clean-and-better-code-in-2020/)

[What are README.MD for](https://medium.com/@saumya.ranjan/how-to-write-a-readme-md-file-markdown-file-20cb7cbcd6f)