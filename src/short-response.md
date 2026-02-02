# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

**Your Answer:**

Flex item is an element within it's Flex container that uses display:flex.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

**Your Answer:**

The main axis refers to flex items flowing in the row direction by default. This is set using flex: direction, the cross axis is perpendicular to this direction, also known as a column. When using justify-content it defines the spacing along the main axis and align-items defines the alignment of elements along the cross axis.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

**Your Answer:**

I would use Flexbox when I want the elements in my container to be one dimensional, I would either use a row or column but if I wanted my elements to be two dimensional I would use CSS Grid and with that i would then be able to arrange them into rows and columns.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

**Your Answer:**

The (fr) refers to fractional unit, it evenly distributes the available space in the grid container to each grid item without overflowing. If we were to use grid-template-columns: 1fr 2fr 1fr, the first and last column would receive 1/4 of the provided space while the second column would receive 2/4.


## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

**Your Answer:**
Media queries allows our CSS to be responsive to the users screen size, If we didn't use it and our design was tailored for a laptop and the user was using a phone they would barely see the content on the page, which is why it is important because it would be hard for them to use the app.

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

**Your Answer:**
Mobile-First Design is a responsive web design that starts with designing for mobile devices first and using media queries to modify that design for progressively larger screens which is easier than starting with a larger screen size and working your way towards a smaller screen size.