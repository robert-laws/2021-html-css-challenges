# UX/HTML/CSS Challenge # 3 - E-Commerce Website

## The Challenge

The third challenge in the UX/HTML/CSS Design and Code Challenge series is an e-commerce website. The rationale for this particular challenge was to find a site that could easily lend itself to use of CSS Grid layout. The inspiration for this challenge comes from the website [Bohemian Traders](https://bohemiantraders.com/), which is an online shop to purchase clothing based in Australia.

The challenge, like [previous](https://robert-laws.com/blog/challenge-one) [challenges](https://robert-laws.com/blog/challenge-two), is to recreate the design of the website homepage ([live version of the final website](https://www.robert-developer.com/challenges/three/)). The focus of this challenge is slightly different than previous challenges in that the focus for this challenge is less on design process and more on application of CSS Grid for mobile and desktop.

<!-- Featured Image -->

## Putting CSS Grid to Work

[CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout) is specification for layout in CSS that makes two dimensional grid systems. CSS Grid has an extensive set of features to create columns, rows, designate parts of the grid for specific purposes, and control alignment in all directions. Because it has an extensive set of features, CSS Grid takes some practice to get comfortable with the features. Thankfully, there are many great resources available to help learn CSS Grid including many paid and free tutorials, several books, and many good websites. Here's a sample of some of the websites I consulted when learning the fundamentals.

#### Learning Resources

- [A Complete Guides to Grid - CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Learn CSS Grid]()https://learncssgrid.com/
- [Grid in CSS](https://cssreference.io/css-grid/)
- [Grid Cheatsheet](https://yoksel.github.io/grid-cheatsheet/)

#### Visual Examples of Layouts

- [Visual Cheatsheet for Grid Layout](https://grid.malven.co/)
- [CSS Layout](https://csslayout.io/)

## Finding a Good Design

The inspirational website for this challenge was a perfect candidate for the use of CSS Grid. Two key features of this website made it a good candidate. First, the design employs a full bleed header, hero section, and footer. And second, the main content area is a series of images contained within a fixed column and laid out in a grid pattern. Traditionally, a layout like this would be somewhat tricky to implement without using a lot of div containers and extensive CSS, especially considering the need to create both a design for mobile and larger screen sizes.

<!-- Screenshot of the inspirational website -->

## Working through the Design

One of the initial steps I take with these challenges is to explore and take apart the design using a UX design tool, Adobe XD in my case. This is an important part of the process to help identify typography, color palette, icon usage, layout patterns, spacing, and components that will be translated in HTML and CSS. I also use the design phase to build a design based on the inspirational website, but with different branding, images, and content. Doing this allows me to retain the important layout and design aspects of the website - which I want to recreate - while using different content so as to not just copy the inspirational website's content.

The result of this process concluded with the production of two finished prototype screens - mobile and desktop - which I would use as the basis for building each with HTML and CSS in the Development phase.

<!-- Image of Combined Design Layout -->

Part of the value of the design process is in planning how to structure the layout and grids that will eventually be created with the HTML and CSS. This design has two major grids - a site grid that would layout the entire page contents and a nested grid for the main content, which mostly included a mosaic of images.
