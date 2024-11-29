# CSS GRID 
### Overview
This project demonstrates the use of CSS Grid to create various responsive layouts. CSS Grid provides a powerful way to create complex web layouts with minimal effort.

The following layouts have been implemented in this project:

Product List Layout
Employee List Layout
Student List Layout
Gallery Layout
Pricing Cards Layout
Each layout uses CSS Grid to achieve a responsive and flexible design.

## How CSS Grid is Used
### 1. Product List Layout
The Product List layout displays a collection of product cards in a grid format. The number of columns adjusts automatically based on the screen size, ensuring that the design is responsive.

Key CSS Grid Properties Used:

display: grid; – Enables the use of CSS Grid for the container.
grid-template-columns: repeat(auto-fill, minmax(250px, 1fr)); – Defines flexible columns that adjust automatically to fit the available space.
gap: 20px; – Sets the spacing between grid items to 20px.
### 2. Employee List Layout
The Employee List layout displays employee cards in a grid format. It uses CSS Grid to ensure that employee cards are arranged neatly in columns, making the layout responsive across various screen sizes.

Key CSS Grid Properties Used:

display: grid; – Enables CSS Grid on the container.
grid-template-columns: repeat(3, 1fr); – Creates 3 equally spaced columns for displaying employee cards.
gap: 20px; – Defines the spacing between the employee cards.
### 3. Student List Layout
The Student List layout displays student information in a grid of cards. The layout adapts to different screen sizes using CSS Grid.

Key CSS Grid Properties Used:

display: grid; – Activates CSS Grid for the container.
grid-template-columns: repeat(4, 1fr); – Defines 4 equal-width columns for the student cards.
gap: 20px; – Specifies the spacing between the cards.
### 4. Gallery Layout
The Gallery Layout displays images in a responsive grid. It adapts the number of columns based on the screen width, ensuring an optimal layout for different devices.

Key CSS Grid Properties Used:

display: grid; – Turns on CSS Grid for the gallery container.
grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); – Automatically adjusts the number of columns to fit the screen size.
gap: 15px; – Sets the spacing between the gallery items.
### 5. Pricing Cards Layout
The Pricing Cards Layout displays different pricing plans in a responsive grid layout. CSS Grid ensures that the cards are evenly spaced and align properly on different screen sizes.

Key CSS Grid Properties Used:

display: grid; – Enables the use of CSS Grid for the container.
grid-template-columns: repeat(3, 1fr); – Creates 3 equal-width columns for the pricing cards.
gap: 20px; – Defines the spacing between the pricing cards.
