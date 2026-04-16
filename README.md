# IS312-Lab3

# Future Technologies Website (Lab 3 - Bootstrap Framework)

## Group Members
1. Vincent Mala - branch `features/vmala`
2. Obert Moses - branch `features/omoses`

## Project Overview
This project was developed as part of Lab Activity 3 for IS312 Web Application Development.  
It demonstrates the use of the Bootstrap framework to create a responsive, multi-page website that showcases technological advances.

## Other classes of Bootstrap. Three Bootstraps findings:
1. .dropdown class is used to indicate a dropdown menu.
2. .border class is used to add a border to an element.
3. .shadow class is used to add a shadow to an element.

## Pages
- **index.html** → Home page introducing future technologies and navigation.
- **innovations.html** → Highlights specific technological advances such as AI and green energy.
- **about.html** → Introduces the team and explains the project purpose.

## Bootstrap Components Used
- **Navbar** → Responsive navigation across all viewports.
- **Jumbotron** → Large header section to capture user attention.
- **Grid System** → Used to organize content into responsive columns.

## Custom Styles
An external stylesheet (`css/style.css`) was created with at least three custom rules:
1. Background for the body.
2. Custom font styling for jumbotron.
3. Border styling for Bootstrap cards.

## Text Styling
Bootstrap text utility classes were applied:
- `.text-muted` for color emphasis.
- `.lead` for highlighted introductory text.

## Images
The image used uses the `.img-fluid` class to ensure responsiveness across devices.

## Spacing
Bootstrap spacing classes such as `.mt-4`, `.mb-3`, and `.p-3` were used for margins and padding.

## jQuery
Linked via `js/script.js`.
Each HTML file includes a jQuery **document ready event**:
```javascript
$(document).ready(function(){
   console.log("Document is ready!");
});
