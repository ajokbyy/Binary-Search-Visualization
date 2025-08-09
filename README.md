🔍 Binary Search Visualization
A simple, interactive Binary Search algorithm visualizer built with HTML, CSS, and JavaScript.
It allows you to enter a number and watch step-by-step how binary search operates within a sorted array, including element highlighting and search progression.

📌 Features
Interactive search — Enter any number to search within a predefined sorted array.

Step-by-step highlighting — Visual feedback on which element is being checked at each step.

Dynamic colors for:

Current element being checked (Yellow)

Found element (Green)

Default elements (Blue)

Time complexity display — Shows O(log n) during execution.

Responsive design — Works well on desktops, tablets, and mobile screens.

📂 Project Structure
text
📦 Binary Search Visualization
├── index.html   # Main HTML page
├── style.css    # (Optional) External CSS file (styles are inline here)
└── script.js    # (Optional) External JS file (currently inline)
🛠️ Technologies Used
HTML5 — Structure of the webpage

CSS3 — Styling and animations

JavaScript (ES6) — Core binary search logic and DOM manipulation

🚀 How to Run
Clone or Download this repository:

bash
git clone https://github.com/your-username/binary-search-visualization.git
Open the index.html file in your browser.

Enter a number into the input box and click Start Search.

Watch the algorithm run step-by-step.

🎯 How It Works
The array is pre-sorted:

text
[2, 5, 8, 12, 16, 23, 38, 45, 56, 72, 91]
Binary Search steps:

Calculate the middle index.

Highlight the current middle in yellow.

Compare it to the target value:

If equal → highlight in green and display index.

If smaller → search in the right half.

If larger → search in the left half.

Repeat until the element is found or search range is empty.

Shows "Element not found" if value doesn’t exist in the array.

🖥️ Live Preview
You can run it locally or host it on:

GitHub Pages

Netlify

Vercel

📊 Time Complexity
Worst-case: O(log n)

Best-case: O(1) (if the element is the middle on the first check)

Space complexity: O(1)

📷 Screenshot Example
(Insert a screenshot or GIF of your visualization here)

📌 Future Enhancements
Allow custom array input.

Animation speed control.

Display number of comparisons.

Support for descending order arrays.
