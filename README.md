📌 Testimonials Grid UI

A clean, modern, responsive Testimonial Grid layout built using HTML & CSS.
This project is inspired by a Frontend Mentor challenge and focuses on creating flexible testimonial cards using CSS Grid, Flexbox, and mobile-first responsive design.

📚 Table of Contents

Overview

The challenge

Screenshot

Links

My process

Built with

What I learned

Continued development

Useful resources

Author

Acknowledgments

🌟 Overview

This project recreates a Testimonial Grid UI similar to those used in dashboards, SaaS platforms, and modern marketing landing pages.
The layout consists of cards in different shapes and sizes arranged using CSS Grid with 4 invisible columns and 3 rows for precise control.

The purpose of this project was to strengthen my skills in:

Advanced CSS Grid layouting

Mobile responsiveness

UI spacing, alignment, and styling

Combining Grid + Flexbox for inner and outer structure

🚀 The challenge

Users should be able to:

View the layout perfectly on desktop, matching the testimonial design

Experience a clean mobile layout where all cards stack full-width

See balanced spacing, consistent alignment, and smooth responsive behavior

Understand how CSS Grid start and end is used to create non-uniform card sizes

🖼️ Screenshot

![Desktop design](<design/Screenshot 2025-12-08 at 08-35-19 Frontend Mentor Testimonial Grid.png>)
![Mobile design](<design/Screenshot 2025-12-08 at 08-37-07 Frontend Mentor Testimonial Grid.png>)

🔗 Links

🧾 Solution Repository: https://github.com/John-Uko/Testimonial-grid.git

🌍 Live Site: https://testimoniallgrid.netlify.app/

🛠️ My process
🔧 Built with

Semantic HTML5

CSS Grid (repeat, gird columns/rows start and end)

Flexbox for mobile responsiveness

Custom variables

Mobile-first responsive design

Testimonial UI design pattern

📚 What I learned

This project taught me several valuable CSS concepts:

🎯 1. Why a 4-column grid is needed

Even though the design looks like 3 columns, using 4 smaller grid columns provides finer control, allowing cards to span:

1 column

2 columns

3 columns

and combine in any pattern

🎯 2. Row/column spanning

I used:

grid-column: start and end;
grid-row: start and end;


to control card sizes perfectly.

🎯 3. Default Grid behavior

I learned that CSS Grid automatically flows items into new rows, even without:

grid-auto-flow: row;


because row-flow is the default.

🎯 4. Mobile responsiveness using Grid

By switching the grid to a single column on mobile:

@media screen and (min-width: 360px) {
    .container{
        display: flex;
        flex-direction: column;
        width: 100%;
    }
}


every card becomes full width.

🎯 5. Combining Grid + Flexbox

Grid handles layout structure, while Flexbox handles mobile responsiveness.

🔄 Continued development

Future improvements I plan to work on:

Convert the entire layout to Tailwind CSS

Add animations on hover and scroll

Rebuild this layout using React components


Increase reusability for dashboard UI templates

🧩 Useful resources

W3School: The Complete Guide to Grid – My go-to reference while building

Frontend Mentor – Project inspiration and UI design samples


👤 Author

John Uko

GitHub: https://github.com/John-Uko

Frontend Mentor: https://www.frontendmentor.io/profile/John-Uko

🙏 Acknowledgments

Special appreciation to the Frontend Mentor community for inspiring the design style and helping me practice real-world layout challenges.