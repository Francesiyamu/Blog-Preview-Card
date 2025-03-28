# Blog Preview Card
 This  a beginner friendly HTML & CSS-only challenge project to help me with HTML and CSS fundamentals, like HTML structure and the box model.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

What I learned
While working on this project, I gained a deeper understanding of the following concepts:

1. Semantic HTML:
I learned how to use semantic elements like <article>, <header>, <footer>, and <time> to create a well-structured and accessible webpage. For example, the <time> element was used to represent the published date in a machine-readable format:

<time datetime="2023-12-21">Published 21 Dec 2023</time>

2. CSS Flexbox:
I improved my skills in using Flexbox for layout design. It helped me align elements like the author section and the blog content efficiently. Here's an example of how I used Flexbox to style the author section:

.author-image {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    gap: 10px;
}

3. Hover and Focus States:
I implemented hover and focus states for interactive elements like buttons and links to enhance user experience. For example:


.header button:hover,
.header button:focus {
    background-color: hsl(47, 88%, 53%);
    outline: none;
}

4. Responsive Design:
I practiced creating responsive layouts using media queries to ensure the design looks good on different screen sizes. For instance:

@media screen and (min-width: 375px) {
    .container {
        max-width: 327px;
        padding: 13px;
    }
}

### Useful resources

- w3schools:  https://www.w3schools.com/tags/tag_time.asp - This is an article which helped me understand  <time> HTML element represents a specific period in time. It may include the datetime attribute to translate dates into machine-readable format, allowing for better search engine results or custom features such as reminders.



## Acknowledgments

I would like to thank Mr. Kelvin for taking the time to review my projects and providing honest feedback on areas where I can improve.

