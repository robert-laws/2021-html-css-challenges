# UX/HTML/CSS Challenge # 1 - Blog Website

## The Challenge

The first challenge in the UX/HTML/CSS Design and Code Challenge series is a blogging website. The inspiration for this challenge comes from the website [We The Parents](https://wetheparents.org), which is a blog intended for parents.

The challenge is to recreate the design of the website homepage. The process begins by breaking down the design with the tool Adobe XD. After that, it's on to VSCode to begin putting together the HTML layout before finally adding the CSS styling.

## Website Structure

The homepage of the website has many common features found on a blogging website including:

- header with different types of navigational links
- content are with a list of blog teasers
- sidebar with narrative and search features
- footer with copyright and additional navigation.

The first hurdle of the challenge was deciding how to divide the webpage into [semantic elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics). The website is divided vertically into three sections, a header, a section with content, and a footer. Within the header are two types of navigation - first a top by with secondary navigational links and a nav with the branding and main navigation. Within the section with content there is a main element, which contains the focal point of the webpage - the individual blog entries. Additionally, within the section with content is a sidebar that consists of an aside with related information to the main content and a section with a site search feature. Finally, the footer contain additional site navigation and content.

<!-- image for semantic sections -->

## Design

With the design, I adopted an [Atomic Design approach](https://xd.adobe.com/ideas/process/ui-design/atomic-design-principles-methodology-101/) to the various elements and their combinations within the overall layout and design. The Atomic Design approach is based on the [atomic design theory](https://bradfrost.com/blog/post/atomic-web-design/) develop by Brad Frost and described in detail in his book [Atomic Design](https://atomicdesign.bradfrost.com/). The basic idea behind atomic design is that components within a design can be built from the ground from the smallest pieces - or atoms - and grow in complexity as they're combined to form molecules and organisms. Once a design has built a list of atoms, molecules and organisms they can be arranged within a templates, and finally populated with content to produce pages.

Since this challenge is fairly easy, the components of the website are relatively uncomplicated from an atomic design perspective. The majority of the content of the site consists of atoms and molecules.

### Atoms and Molecules making up the Sidebar Section of the Template

<!-- image of sidebar atoms -->

This image shows the atoms used within the sidebar section of the template. An important feature of atoms is that they cannot be broken down further without losing their meaning and usefulness in a design.

<!-- image of sidebar molecules -->

This image moves forward and combines the atoms together to form two molecules. What stands out to me about what makes a molecule a distinctive unit and not just two atoms grouped together is the relationship and dependency between the combination of atoms. For example, in the molecule entitled _Sidebar Content_ in the image above, the image and paragraph must depend upon each other in some way for this to be considered a molecule. In other words, the image must depend on the paragraph to give essential contextual meaning to the image and the paragraph must depend on the image in order for the text to be meaningful. If the image and paragraph are unrelated to each other, then this does not seem to me to make a molecule since either the image or paragraph could be removed and there would be no change in the meaning of the image or paragraph on its own.

The same applies to the _Sidebar Search_ molecule. The heading, text input, and button all depend on each other to be meaningful. The heading provides important contextual information about what is being searched when someone enters words into the text input and can submit the search using the button. The text input depends on the heading to provide context to how a user will enter text into the input and submitting their search query only after clicking the search button. The button depends on the heading and the text input to make sense of the expected outcome of clicking the button.

The _Sidebar Search_ becomes a molecule based on the dependency between the atoms. The content information of each atoms matters in this case since different content could be used in different combinations to the same effect. For example, if the button text said "Search Blog Posts" then it could be argued that the text input and button don't necessarily depend on the heading to be meaningful and the heading therefore could be removed. The text input and button would still exist as a molecule.

### Final Design Template

For this challenge, applying atomic design was useful, but it is also a work in progress. Since this is the first challenge, part of the process is figuring out a good workflow and the best way to produce a final result. The design produced in the end is correct from a visual point of view - it visually matches the original website used for inspiration. The underlying process of building a design from the ground up, however, will need refinement. Applying an atomic design approach may work best by breaking a design down into its constituent atoms and then rebuilding it into molecules and organisms. Parallel with this process is the creation of a template in which atoms, molecules, and organisms are placed. The process could stop here, but to give the challenge more realism, actual content could be used to produce pages that are meaningful as well as visual consistent with the original inspirational website.

<!-- image of final design template -->

## Code
