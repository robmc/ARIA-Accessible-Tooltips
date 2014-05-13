ARIA-Accessible-Tooltips
========================

Accessible tooltips using various ARIA attributes and some CSS trickery.

I initially wrote this to toggle visibility of the tooltips using JavaScript but then refactored to achieve this with CSS upon finding the following source:
http://heydonworks.com/practical_aria_examples/

This method uses what is known as an Adjacent Sibling Selector in CSS:
http://reference.sitepoint.com/css/adjacentsiblingselector

This example utilizes this method on form fields, a link element, and a simulated icon/button.
