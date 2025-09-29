# X Clone Mini Project

This project is a functional, interactive clone of the X (formerly Twitter) feed, built as a key module in the Scrimba Frontend Developer Career Path. It demonstrates core JavaScript concepts for building dynamic and responsive web applications.

## 🚀 Live Demo

[https://scwimba.netlify.app/]

## ✨ Features & Skills Learned

This project was built from the ground up and showcases a wide range of essential frontend development skills:

*   **Dynamic HTML Rendering:** Generating the entire tweet feed from a JavaScript data object using template literals.
*   **Event Handling:** Using a single event listener on the `document` to efficiently manage all user interactions (likes, retweets, replies).
*   **Data Attributes:** Leveraging `data-*` attributes to pass unique IDs from the HTML to JavaScript, connecting UI elements to their corresponding data.
*   **Array Manipulation:**
    *   Using `.forEach()` to iterate over data arrays and build HTML.
    *   Using methods like `.filter()` or `.find()` to locate specific objects within an array based on their ID.
*   **State Management:**
    *   Modifying object properties (e.g., `likes`, `retweets`, `isLiked`) to update the application's state.
    *   Toggling boolean values with the logical NOT operator (`!`) to track state changes.
*   **Conditional Rendering & Styling:**
    *   Applying CSS classes dynamically (e.g., a "liked" class) to reflect state changes in the UI.
    *   Using `.classList.toggle()` to show and hide reply sections.
*   **External Libraries:**
    *   Integrating **Font Awesome** via a CDN to add icons.
    *   Using the **UUID** library via a CDN to generate unique identifiers for new tweets.

## 🛠️ How To Run Locally

1.  Clone the repository:
    ```sh
    git clone https://github.com/Ayoubxpy/X-Clone-Mini-Project.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd X-Clone-Mini-Project
    ```
3.  Open the `index.html` file in your browser.

---

Built with guidance from the [Scrimba Frontend Developer Career Path](https://scrimba.com/).
