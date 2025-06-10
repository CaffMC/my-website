# Website to be potentially used for my small landscaping, construction, and manual labor business.

## Changes for Mod 9
1. I noticed that on your home page, at roughly 1180x1360px, that your picture cuts off the bottom of your tagline (the g specifically).

Fixed this by changing spacing of the h1 and h2, made the h1 and h2 text smaller, and made the images' max-height slightly less. 

2. For accessibility, make sure each icon (like the shovel, leaf, etc.) includes alt text so screen readers can identify them.

Went to each html file and added alt atributes to images. I didn't add aria-labels or anything to the icons because they are solely decorative. Instead I added aria-hidden="true".