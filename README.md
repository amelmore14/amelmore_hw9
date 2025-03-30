# Business Analytics Student Survey

## Description

The Business Analytics Student Survey is a web-based survey designed to gather insights from students enrolled in the Business Analytics and Information Systems (BAIS) program. This survey aims to collect demographic information and feedback from students, which will be used to better understand the BAIS student population. The survey is divided into three pages and can be easily completed in less than a minute.

## Best Practices for Forms

In designing the Business Analytics Student Survey, I have adhered to several best practices to ensure the form is both functional and user-friendly.

First, I utilized HTML5 form validation to ensure that required fields are filled out before submission. This helps prevent incomplete or incorrect submissions, ensuring that all necessary data is collected. For instance, fields such as "My home country is" and "My home town is" are required, and the user cannot proceed without providing this information. Additionally, I used `autofocus` attributes where necessary, such as in the first text field for "My home country is," making it easier for users to begin filling out the form without having to click into the field. For multi-choice and checkbox questions, proper labels and input elements were used to ensure that all questions are clearly understandable and easy to interact with.

Secondly, I integrated clear form grouping and appropriate labels for each question. This improves the user experience by making the form more structured and easy to navigate. The use of tooltips for certain questions (e.g., "My home town is") provides additional clarification without overwhelming the user with too much text at once. I also utilized dropdown menus for selection-based questions, such as selecting a U.S. state or rating the impression of the BAIS major. These features enhance usability and guide the user smoothly through the survey.

## User Accessibility

Accessibility is a key priority in this web form to ensure that all users, including those with disabilities, can effectively engage with and complete the survey. To meet accessibility standards, I made use of semantic HTML elements, such as `<label>` for form fields, which ensures that screen readers can properly identify the form elements and their associated labels. For example, each dropdown menu and checkbox has a corresponding `<label>`, which improves the accessibility for users using assistive technologies.

Additionally, I ensured that the form is fully navigable via the keyboard, allowing users with motor disabilities to interact with the survey without the need for a mouse. The form uses clear error messages and validation feedback to guide users in case of missing or incorrect input. For visual accessibility, the form employs readable fonts, and responsive design principles to ensure that the form is usable on both mobile and desktop devices. Furthermore, tooltips are provided to assist with understanding specific questions, and all interactive elements, such as buttons and links, are clearly distinguishable from the rest of the content.
