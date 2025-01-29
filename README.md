# intern-day-2
Basic HTML is the fundamental language used to structure content on the web using tags like headings, paragraphs, and links. It forms the backbone of web pages, allowing developers to organize and display text, images, and other elements in  

# Intern Day 2 - Learning HTML Lists and Tables

## Overview
This repository contains notes and exercises from my first day as an intern. On Day 1, I learned about creating and using lists and tables in HTML. Below is a summary of the concepts I covered and examples of each.

## Learning Objectives
- Learn how to create and use lists in HTML
- Understand the structure and usage of ordered, unordered, and description lists
- Learn how to create tables in HTML
- Practice basic table structure and formatting

## Topics Covered

### 1. **HTML Lists**
HTML provides three main types of lists:

#### a. **Unordered Lists (`<ul>`)**
   - Unordered lists display items with bullet points by default.
   - Each list item is defined with the `<li>` tag.
   - Example:
     ```html
     <ul>
         <li>Item 1</li>
         <li>Item 2</li>
         <li>Item 3</li>
     </ul>
     ```

#### b. **Ordered Lists (`<ol>`)**
   - Ordered lists display items with numbers (or letters) to show the order.
   - Each item is still wrapped in an `<li>` tag.
   - Example:
     ```html
     <ol>
         <li>Step 1: Gather ingredients</li>
         <li>Step 2: Mix ingredients</li>
         <li>Step 3: Bake</li>
     </ol>
     ```

#### c. **Description Lists (`<dl>`)**
   - Description lists are used for pairs of terms and descriptions.
   - Each term is defined with the `<dt>` tag and its description with the `<dd>` tag.
   - Example:
     ```html
     <dl>
         <dt>HTML</dt>
         <dd>HyperText Markup Language</dd>
         <dt>CSS</dt>
         <dd>Cascading Style Sheets</dd>
     </dl>
     ```

#### d. **Nesting Lists**
   - Lists can be nested inside one another to create more complex structures.
   - Example (unordered list inside an ordered list):
     ```html
     <ol>
         <li>First item
             <ul>
                 <li>Subitem 1</li>
                 <li>Subitem 2</li>
             </ul>
         </li>
         <li>Second item</li>
     </ol>
     ```

### 2. **HTML Tables**
Tables in HTML are used to display data in a structured way with rows and columns. The basic structure involves the following tags:
- `<table>`: Defines the table itself.
- `<tr>`: Defines a row in the table.
- `<th>`: Defines a header cell.
- `<td>`: Defines a data cell.

#### a. **Basic Table Structure**
   - Example of a simple table with a header row and data rows:
     ```html
     <table border="1">
         <tr>
             <th>Name</th>
             <th>Age</th>
             <th>City</th>
         </tr>
         <tr>
             <td>John</td>
             <td>25</td>
             <td>New York</td>
         </tr>
         <tr>
             <td>Jane</td>
             <td>30</td>
             <td>Los Angeles</td>
         </tr>
     </table>
     ```

#### b. **Table with Multiple Rows and Columns**
   - Example of a table displaying student grades:
     ```html
     <table border="1">
         <tr>
             <th>Student</th>
             <th>Math</th>
             <th>Science</th>
             <th>History</th>
         </tr>
         <tr>
             <td>Alice</td>
             <td>85</td>
             <td>90</td>
             <td>88</td>
         </tr>
         <tr>
             <td>Bob</td>
             <td>75</td>
             <td>80</td>
             <td>70</td>
         </tr>
     </table>
     ```

#### c. **Table Attributes**
   - You can add attributes like `border`, `cellspacing`, `cellpadding`, and `width` to style the table.
   - Example with `border`:
     ```html
     <table border="2">
         <tr>
             <th>Product</th>
             <th>Price</th>
         </tr>
         <tr>
             <td>Apple</td>
             <td>$1.00</td>
         </tr>
         <tr>
             <td>Banana</td>
             <td>$0.50</td>
         </tr>
     </table>
     ```

## Practical Exercises
On Day 1, I worked on the following exercises:
- Created an unordered list of my favorite foods.
- Created an ordered list with steps to complete a task (e.g., making tea).
- Created a description list for HTML tags and their definitions.
- Designed a table to display student data (e.g., grades, names, subjects).

## Next Steps
- Continue practicing HTML tables, experimenting with more advanced table features.
- Learn about CSS to style lists and tables.
- Explore additional HTML elements like forms, images, and links.

## Conclusion
Day 1 was a productive introduction to HTML lists and tables. I learned the basic structure and syntax for creating different types of lists and tables, which are essential for organizing content in web development.

---

Feel free to reach out if you have any questions or would like to discuss HTML further!


