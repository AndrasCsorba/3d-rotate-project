# 3d-rotate-project
This project made with just html and css.Project Overview
LIVE DEMO ===>>> https://andrascsorba.github.io/3d-rotate-project/

This project is a responsive image slider that uses HTML, CSS, and JavaScript. The slider allows users to view a series of images and navigate between them using previous and next buttons. It supports dynamic image transitions and adapts to various screen sizes, providing a modern and elegant interface.

1. Features
Responsive Design: Adapts to different screen sizes using media queries.
Image Transitions: Smooth sliding transitions between images.
Navigation Controls: "Next" and "Previous" buttons to control the flow of images.
CSS Animation: Uses CSS animations for transitions like blur effects and rotating elements.
Custom Fonts: Includes fonts like "Bebas Neue" and "Poppins" for aesthetic typography.

2. Technologies Used
HTML5: Markup structure for the slider and overall page.
CSS3: Styling for layout, animations, and responsiveness.
JavaScript (ES6): To handle the logic of the image slider (navigation and dynamic styling)
4. File Structure
Is simple.

3. Setup Instructions
Clone the Repository
Clone the project repository from GitHub using the following command:

bash
Code kopieren
git clone https://github.com/your-username/image-slider.git
Open the Project

Navigate to the project folder and open index.html in a web browser to see the image slider in action.

Customizing Images
Replace images in the /img folder and update the CSS variable --url in the HTML to change the background images of the slides.

4. CSS Breakdown (style.css)
Key features of the style.css file include:

Custom Properties: CSS variables are used for the slider’s width and image size:


Slider Design: Each slider item consists of an image and text content. The background image is set using the --url custom property:


5. JavaScript Functionality (app.js)
The app.js file provides the logic for navigating between slider items.


This logic ensures that when you click the "Next" or "Previous" button, the correct slide becomes active, and the previous one is hidden.

6. Customization
You can easily customize the slider by:

Changing the images in the img/ folder and updating the CSS variable for each slide.
Modifying the content inside each .item element in the HTML file (titles, descriptions).
7. Conclusion
This project demonstrates how to build a responsive image slider using HTML, CSS, and JavaScript. It uses modern CSS techniques like custom properties and media queries to ensure the layout is responsive and visually appealing across different devices. The JavaScript handles the basic logic for navigating between slides, providing a smooth user experience.

8. Future Improvements
Autoplay Functionality: Add autoplay to automatically transition between slides after a set interval.
Swipe Gesture Support: Implement swipe gestures for touch devices.
Lazy Loading: Integrate lazy loading for images to optimize performance.

Merci
