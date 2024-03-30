# Travel Destination Diary 🌍✈️

Welcome to the **Travel Destination Diary!**

**Description:**

This interactive web application allows users to create personalized digital post-it notes for each of their travel experiences. Capture memories, jot down reflections, and even upload photos to customize your diary entries. With options to edit text content and adjust post colors, you can tailor your entries to perfectly encapsulate the essence of each adventure. Whether you're revisiting past trips or planning new ones, the Travel Destination Diary is your go-to platform for documenting and sharing your travel stories.

**Live Website:** [Travel Destination Diary](https://chakrikaanousha.github.io/Travel-Destination-Diary/)

**Code Highlights:**

1. **HTML, CSS, JavaScript:**
   - **HTML:** Provides the structure and content of the web page.
   - **CSS:** Styles the HTML elements to enhance the visual appearance and layout.
   - **JavaScript:** Adds interactivity and functionality to the web page.

2. **Form Submission:**
   - **Functionality:** Allows users to input details such as the place visited, experience, and optional image upload through an HTML form.
   - **Functions Used:** Basic HTML form elements (`<input>`, `<textarea>`, `<button>`) for user input.

3. **Dynamic Element Creation:**
   - **Functionality:** Dynamically creates and appends diary entries based on user input, allowing users to add multiple entries without refreshing the page.
   - **Functions Used:** `document.createElement()` to create HTML elements dynamically, and `appendChild()` to add them to the DOM.

4. **Customizable Post-It Notes:**
   - **Functionality:** Provides users with the option to select their preferred post color for each diary entry, enhancing personalization.
   - **Functions Used:** Utilizes an `<input type="color">` element to allow users to choose a color.

5. **Edit Functionality:**
   - **Functionality:** Enables users to edit text content and post color of existing diary entries after they've been created.
   - **Functions Used:** 
     - For editing text content: Utilizes the `prompt()` function to prompt users for new text input, and updates the existing text accordingly.
     - For editing post color: Similar to text editing, prompts users for a new color value and updates the background color of the entry.

6. **Responsive Design:**
   - **Functionality:** Ensures the web application adapts and provides an optimal viewing experience across various devices and screen sizes.
   - **Functions Used:** Utilizes CSS media queries and flexible layout techniques to adjust the layout and styling based on the viewport size.

These functions collectively create a user-friendly and interactive experience for documenting travel memories in the Travel Destination Diary web application.
