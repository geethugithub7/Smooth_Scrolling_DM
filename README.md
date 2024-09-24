# Smooth_Scrolling_DM
This HTML and CSS code creates a simple webpage with smooth scrolling between two full-screen sections. Each section has a clickable link that scrolls the page smoothly to the other section.   The project was built after attending a class on the DebugMedia YouTube channel.

HTML Structure:
The <html> document is structured into two sections (section-1 and section-2) using <div> elements.
Each section has a link:
In section-1, the link scrolls to section-2.
In section-2, the link scrolls back to section-1.
CSS:
Smooth Scrolling: The scroll-behavior: smooth; property in the html selector ensures smooth scrolling between sections when the links are clicked.
Full Screen Divs: Each <div> is set to be 100vh (full viewport height) with centered content both horizontally and vertically using Flexbox (align-items and justify-content).
Background Image & Color: The two sections (#section-1 and #section-2) have background images and fallback colors.
Background images are set with background-image, and they cover the entire section using background-size: cover.
Links Styling: The links are styled with:
Font and Color: A sans-serif font, white text, a black background, and bold font.
Padding: Padding makes the links appear as buttons.
Mix-blend-mode: This is used to blend the text over the background, though it may behave differently depending on the images and browsers.
Issues to Address:
The images for the sections are referenced (images/section1.jpg and images/section2.jpg), but these files need to be present in the specified directory for the background to load correctly.
The CSS for font-style: bold; should be replaced with font-weight: bold; for proper bold text rendering.
