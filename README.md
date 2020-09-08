# Breaking Ice

## Instructions to view

Simply clone the project, or download the zip, and open the index.html file to view.

## About the build

I approached this build by printing off a copy of the PDF provided and identified the global styles I'd need - typography (type, sizes, weight), colours, button styles and reusable components.

To start development I set up a simple localhost environment with SCSS and live-reload. I knew the page needed a 12-col grid and would be responsive so I added bootstrap to speed up development. I knew one of the components was a carousel so I added Slick JS/CSS libraries. I then added my base styles - variables, fonts, typography (I ended up branching away from the design guide styles just to make it more inline with the design I had), layout, etc. so I had all the global elements ready to use when I came to building out the components.

## The components

### The header

A simple component with a background image and content positioned with flex, vertically and horizontally within it, and a chevron positioned absolutely at the bottom.

### The tiled components

Three tiles showcasing the product which I flexed in a row next to each other for desktop and stacked vertically for mobile. From the design I could see there was a hover style demonstrating which tile you were mousing over. To do this I added a grey border bottom and a transform-scale style to make the image pop on mouseover.

### Content block

A fairly straightforward content block which I could reuse further down the page. I determined my grid layout for mobile and desktop and I had set up my base styles so it was a matter of adding the heading/paragraph markup and it was complete.

### Full width background component

Another component I could reuse a few times for this build. A simple background image with content inside of it. I created a default size and added a flexible-copy modifier to account for situations where you wanted the copy to determine the height of the component.

### Carousel/Product component

The most complex component on the page. A carousel with product components inside of it. I used slick for the carousel functionality and showed four products in desktop and one product for mobile. The products themselves were straightforward - an image product and content below. I added a slight scale effect on mouseover of the products to make them more dynamic.

## Final thoughts

Overall it was a fairly straightforward build. I didn't modify the design too much but added interaction where I saw fit. It sticks to a 12-col grid layout and works seamlessly in mobile. Usually I’d use browserstack to browser/device test but my subscription has ended so tested on the browsers/devices I had available on my mac. The page is also built in a semantic and accessible way.