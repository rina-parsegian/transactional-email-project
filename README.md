# Transactional Order Confirmation Email

A responsive transactional order confirmation email built with HTML and CSS to practice email-safe development techniques, responsive layouts, and cross-client considerations.

## Live Demo

[View the Live Email](https://rina-parsegian.github.io/transactional-email-project/)

## Project Overview

This project recreates an e-commerce order confirmation email using table based layouts and email safe HTML and CSS.

The goal was to practice building a structured transactional email while working within the limitations of email clients. The layout includes order details, product information, pricing, shipping and payment information, and a responsive footer.

## Features

- Responsive transactional email layout
- Table-based structure for email compatibility
- Inline CSS
- Order confirmation and product details
- Order subtotal, shipping, and total
- Customer shipping and payment information
- Responsive two column layouts
- Mobile column stacking
- Social media footer
- Image alt text and accessibility considerations
- Email-safe font stacks
- Presentation tables using `role="presentation"`

## Responsive Design

Media queries and reusable classes were used to adapt the email for smaller screens.

The mobile layout includes:

- Reduced horizontal padding
- Stacked content columns
- Responsive product information
- Mobile-friendly spacing
- Layout testing at narrow screen widths

## What I Practiced

Through this project, I practiced:

- Structuring HTML emails with nested tables
- Using `<tr>` and `<td>` elements for layout
- Applying inline CSS for email-client compatibility
- Using HTML attributes such as `width` and `align` as fallbacks
- Creating responsive layouts with media queries
- Stacking table columns on mobile
- Working with images inside email layouts
- Adding descriptive image alt text
- Using `role="presentation"` for layout tables
- Testing desktop and mobile layouts
- Organizing email code into clearly labeled sections

## Technologies Used

- HTML
- CSS
- VS Code
- Git & GitHub
- GitHub Pages

## Key Takeaway

Building this project helped me understand how HTML email development differs from traditional web development. Instead of relying on modern layout systems such as Flexbox or CSS Grid, email development often requires table based layouts, inline styling, HTML fallbacks, responsive media queries, and careful testing.

The project gave me practical experience creating a transactional email while balancing visual design, responsive behavior, accessibility, and email client limitations.
