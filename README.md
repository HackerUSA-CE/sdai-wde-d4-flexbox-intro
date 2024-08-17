
# Intro to Flexbox

## Description

This introductory activity will help you learn and practice CSS Flexbox properties including `display`, `flex-direction`, `align-items`, and `justify-content`. Flexbox is a powerful layout module in CSS that allows you to design complex layouts with ease and flexibility. By mastering these properties, you'll be able to create responsive and adaptive web layouts that work seamlessly across different devices and screen sizes.

This activity is meant to be done together as a class.

---

## Learning Outcomes

1. Understand and apply the display property to create a flex container.
2. Use the flex-direction property to control the direction of flex items.
3. Utilize the justify-content property to align flex items along the main axis.
4. Apply the align-items property to align flex items along the cross axis.
5. Create responsive and adaptable web layouts using CSS Flexbox.

---

## Steps

1. **Setup the Project:**
   - Create a new folder for your project.
   - Inside the folder, create three files: `index.html`, `styles.css`, and `README.md`.
   - Copy the provided HTML, CSS, and README content into their respective files.

2. **Understanding the HTML Structure:**
   - The HTML file contains a container div with four child divs, each representing a box.

3. **Styling with CSS:**
   - Open `styles.css` and add the following base styles:

   ```css
   body {
       display: flex;
       justify-content: center;
       align-items: center;
       height: 100vh;
       margin: 0;
       background-color: #f0f0f0;
   }
   ```

   - Next, add styles for the container:

   ```css
   .container {
       display: flex;
       flex-direction: row; /* Change to column for vertical layout */
       justify-content: space-between; /* Experiment with center, flex-start, flex-end, space-around */
       align-items: center; /* Experiment with flex-start, flex-end, stretch */
       width: 80%;
       height: 60vh;
       background-color: #fff;
       border: 2px solid #ccc;
       box-shadow: 0 0 10px rgba(0,0,0,0.1);
   }
   ```

   - Finally, add styles for the boxes:

   ```css
   .box {
       width: 100px;
       height: 100px;
       display: flex;
       justify-content: center;
       align-items: center;
       background-color: #4CAF50;
       color: white;
       font-size: 1.2em;
       border: 2px solid #333;
   }

   .box1 { background-color: #FF5733; }
   .box2 { background-color: #33FF57; }
   .box3 { background-color: #3357FF; }
   .box4 { background-color: #F0A500; }
   ```

4. **Experimenting with Flexbox:**
   - Change the `flex-direction` property of the container to `column` and observe how the layout changes.
   - Try different values for `justify-content` such as `center`, `flex-start`, `flex-end`, `space-around`, and `space-between`.
   - Experiment with the `align-items` property using values like `flex-start`, `flex-end`, `center`, and `stretch`.

5. **Playing with Box Styles:**
   - Change the background color of each box using different colors.
   - Adjust the width and height of the boxes to see how Flexbox handles the sizes.

6. **Bonus Challenge:**
   - Add more boxes to the container and see how Flexbox handles the new elements.
   - Create a nested Flexbox container inside one of the boxes and apply Flexbox properties to it.
