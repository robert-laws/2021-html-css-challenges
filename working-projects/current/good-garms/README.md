# UX/HTML/CSS Challenge # 5 - E-Commerce Website

## The Challenge

The fifth challenge in the UX/HTML/CSS Design and Code Challenge series is an e-commerce website. This challenge aims to combine several techniques that were applied in previous challenges including CSS Grid, Flexbox, and responsive design. Expanding on these features, this challenge aims to add implementation of accessibility standards. The inspiration for this challenge comes from the website [Good Garms](https://www.goodgarms.com/), an online shop to purchase clothing that prioritizes sustainability.

The challenge, similar to ([previous challenges](https://www.robert-developer.com/challenges/)), is to recreate a design based on another website that serves as inspiration. The additional challenge this time is to also focus on the accessibility of the website while also creating an interesting and modern layout and design. The goal for this part of the challenge is to meet the accessibility standards as outlined in the [WAI-ARIA Guidelines](https://www.w3.org/WAI/standards-guidelines/aria/).

<!-- Featured Image -->

## Designing with Accessibility in Mind

For any web developer working in 2021, it's essential to place accessibility high on the list of development priorities whenever starting a new project. Sometimes this means being mindful of best practices for using [HTML sectioning elements](https://www.w3.org/TR/wai-aria-practices-1.1/examples/landmarks/HTML5.html). It also means making wise use of WAI-ARIA Guidelines and implementing techniques like "skip to content" links to maximize the accessibility of any website.

The steps to taken to implement accessibility feature in this challenge are aligned with the goals for the [WCAG (Web Content Accessibility Guidelines) 2.0 Guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/), with particularly emphasis on [WCAG guiding principles](https://www.w3.org/WAI/standards-guidelines/wcag/glance/) of making websites 1) Perceivable, 2) Operable, 3) Understandable, and 4) Robust.

Ultimately, the goal for this and all accessible websites is to make them as usable for those with disabilities as they are for those without. This is challenging and requires a lot of reflection and planning.

## A Fresh and Modern Design

The [Inspiration Website - Good Garms](https://www.goodgarms.com) presented many opportunities to implement an modern design with some really interesting layout and content features. The website is an e-commerce website that is focused on selling clothing that is sustainable and purposely aims to be different. The goal is to create a fashion brand that is open about its production, business values, and goals to provide excellent products with minimal impact on the environment.

<!-- Inspirational Website Screenshot -->

As for design considerations, the inspirational website offers many interesting challenges. First, the layout of the home page appeared to be perfect for using CSS Grid, especially for the image cards of the different clothing products. A unique take on this is that the website that I'm designing based on the inspirational website will also use cards, but an indeterminate number of them. This is because the concept for a website that has many cards is that they would be dynamically loaded from external data. Because of this, a good approach is to use a system that auto-places cards without using a pre-defined HTML structure since the cards will not be hard coded. Additionally, the layout system should accommodate both desktop and mobile device layouts.

The header section, by contrast, could be laid out in a straight-forward manner by using Flexbox. This is because the layout is in one direction instead of being multidirectional and more "grid-like." The footer could be laid out in either with Flexbox or CSS Grid. The reason to use CSS Grid is because there are multiple columns that have different widths.

## Design
