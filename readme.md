### Moneypenny Task

#### 1. Buy Now button fix

- .product-price-btn::after is interfering with button hover behaviour. However, anticipating this styling is included by design, I have left it there and added "pointer-events: none" to its properties which allows the hover animation to work.

#### 2. Image border fix

- index.html line 13 - clas="product-img" was misspelled and therefore class was not defined. Should be class="product-img". Fixed spelling error to allow class to be defined correctly and picked up in the CSS file. Image border radius now corrected.

#### 3. Image optimisation

- Used Squoosh to compress image into a .webp format, reducing file size from 1.45mb to 494kb. This will allow for faster image loading with little to no reduction in image quality.

#### 4. Other nice to haves

- Refactored using SCSS to allow for nesting and better organisation. Although I have not created any here, variables and mixins would be beneficial for reusable elements if the page was to be developed into a larger site.

- Move img dimensions into SCSS, added alt to img.
