Group members
Mache Esanrt 2020907593 and Haansende Katrina Milumbe 2021532399

Page descriptions
index.html (Home Page)
Description:
The home page presents a warm welcome with a hero banner featuring a background image and centered welcome text. It includes a shared header, navigation bar, and footer. The main content section uses a Flexbox layout to display two side-by-side sections: an introduction area and a sidebar listing highlights.

Features Used:
Selectors: HTML elements (e.g., <header>, <nav>, <section>, <aside>) are targeted for styling.
Flexbox: Used in the .content container to align the intro and sidebar horizontally.
Media Queries: Although basic in the sample, they can be applied for further responsiveness.
Consistent Navigation: Shared across pages for uniformity.

services.html
Description:
This page is dedicated to showcasing multiple service offerings with individual “service cards” laid out using CSS Grid. Each card contains an icon (or image), a heading, and a brief description. The page maintains a consistent header, navigation bar, and footer.

Features Used:
Selectors: Classes like .grid, .card, and element selectors for images, headings, and text.
CSS Grid: The .grid container leverages a responsive grid layout (using grid-template-columns and gap) to evenly distribute the service cards.
Hover Effects: Cards have transitions applied on hover for a subtle lift and shadow effect.
Consistent Structural Elements: Shared header, nav, and footer sections.

contact.html
Description:
This page features a styled HTML5 contact form that collects the user’s name, email, subject, and message. The form includes built-in HTML5 validation using attributes like required and type, ensuring that users provide valid data. The form layout is built with CSS Grid to arrange fields responsively. Subtle animations enhance the user experience, with focus transitions for form fields and a hover effect for the submit button.

Features Used:
Selectors: Specific selectors for form elements, input fields, labels, and the button.
CSS Grid: Used to structure the form into a responsive layout that adapts to different screen sizes.
HTML5 Validation: Utilizes attributes such as required and appropriate input types (e.g., email) for basic validation.
Animations: Field focus transitions and button hover effects provide a more interactive experience.

4. style.css
Description:
This central stylesheet applies a global reset, responsive image handling, and consistent styling across all pages. It styles the navigation bar with Flexbox for easy alignment and spacing, and it also defines layouts using both Flexbox (for headers, navs, and various containers) and CSS Grid (for the service cards and contact form).

Features Used:
Selectors: Global selectors (*, img, etc.) along with class and element selectors for navigation, containers, and specific sections.
Flexbox & CSS Grid: Demonstrates two layout techniques: Flexbox for navigation and some containers, and Grid for more structured content such as cards and forms.
Media Queries: Three breakpoints (max-width: 1024px, max-width: 768px, and max-width: 480px) adjust layouts, paddings, and font sizes for various screen sizes.
Animations: A keyframe animation (fadeInUp) is defined and applied to animate elements smoothly.
Hover/Focus Transition: Applies a transition effect on navigation links and form fields to improve user interaction.
