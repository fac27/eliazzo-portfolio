## 1. Structure a site using semantic HTML to aid accessibility

We created a simple mock agency website with a focus on using concise semantic html that allowed users with varying accessibility to access and manouver the site. 

## 2. Ensure a web page is readable for screen readers

To ensure the web page is readable for screen readers, we ensured we were using the correct < h > elements with only one < h1 > tag on the page. We included detailed alt tags so that users were informed of the img contents in instances where they could not see the img itself. We styled the page in order to meet the accessibility requirements (see 3).


## 3. Ensure our UI has sufficient colour contrast so that everyone can perceive it comfortably

![Team screenshot with contrast](/Images/Team%20screenshot%20.png)



## 4. Use various tools to check that our website meets accessibility criteria

![Lighthouse check](/Images/Lighthouse.png)

We used the Chrome "Lighthouse" tab in the Developer Tools which can run different types of tests on a page, including "Accessibility". This informs you of obvious failures like low colour contrast or missing image alt text. A limitation of Lighthouse is that it cannot catch more complex problems, like a custom component that cannot be controlled with the keyboard. In order to overcome this we manually tested the page using a screen reader.

## 5. Use CSS media queries to ensure our content is always presented effectively on screens of different sizes

![Mobile view](/Images/Mobile%20view.png)

## 6. Demonstrate a mobile-first approach to building a website

A mobile-first approach to styling means that styles are applied first to mobile devices. Advanced styles and other overrides for larger screens are then added into the stylesheet via media queries [(zellwk.com).](https://zellwk.com/blog/how-to-write-mobile-first-css/)

We addressed the mobile first learning too late in the project and due to time constraints were unable to apply the approach. We made the page as responsive as possible without using media queries and included media queries only when absolutely necessary. Moving forward, I will definitely be adopting the mobile first approach at the earliest stages of my project.

## 7. Use CSS variables to apply repeated colours to HTML elements

![CSS primitives](/Images/Primitives-screenshot.png))

The above code demonstrates our use of CSS layout primitives which were applied to multipled elements in the HTML. Some particularly useful primitives were the text-x primitives which we used to size different texts. 

## 8. Use CSS Flexbox to style children in a single-direction layout (ie a row or a column)

![CSS Flexbox](/Images/Flex%20screenshot.png)

Each page was styled using a flexbox primitive. The above image features multiple CSS Flexbox as it was applied to the entire page but also within elements on the page such as the navbar and the 'About us' grey box section.

## 9. Use CSS Grid to style children in two-direction layout

![CSS Grid](/Images/Grid%20screenshot.png)

The 'Services' page was styled using grid to demonstrate our understanding of both flexbox and grid. The page is styled in a one-direction layout. If time permits, I would like to return to this and restyle the page in two-direction layout.


## 10. Ensure our Git commit history tells a coherent story

![Git history](/Images/Project%20screenshot.png)

We created an issue for every change and completed the issue via the relevant branch. We linked our issues to the github project feature.

## 11. Use the appropriate input types in HTML forms for gathering different types of information

![Form code](/Images/Form%20sreenshot.png)

The above code demonstrates our use of < form >, < label >, and < input > and < button > tags. The < input > and < button > tags feature the appropriate type attributes.
