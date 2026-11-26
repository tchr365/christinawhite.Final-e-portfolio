CHRISTINA WHITE — E-PORTFOLIO

GET STARTED
1. Extract the ZIP file before opening the website.
2. Keep index.html, style.css, and script.js together in the same folder.
3. Open index.html in a web browser.
4. Edit these files in a plain-text code editor to customize your portfolio.

WHAT EACH FILE DOES
index.html — page content, navigation, headings, and contact details.
style.css — colors, fonts, spacing, cards, buttons, and responsive layout.
script.js — mobile menu, dropdown behavior, project URLs, and link feedback.

ADD YOUR PROJECT URLS
At the top of script.js, find the projectLinks object. Paste each project's
URL between the empty quotation marks. Both its card button and corresponding
dropdown item will use that URL. Configured links open in a new tab.

Key                    Project
svgLogo                SVG Logo
inkscapeBookcover      Inkscape Created Bookcover
aiBookcover            AI Created Bookcover
interactiveQuiz        Interactive Quiz
customDragDrop         Customized Drag-and-Drop
aiDragDrop             AI Drag-and-Drop
traditionalVideo       Traditional Video
aiVideo                AI Video
animation              Animation
screencast             Screencast

Example using a local project:
  svgLogo: "projects/my-logo.svg",

Empty project URLs show "This project will be available soon." The email and
LinkedIn links already use the contact information you provided.

DESIGN NOTES
The desktop layout has five rows: About Me; three projects; three projects;
E-Portfolio; Contact Me. The Contact Me card is half the E-Portfolio card's
width and height when its contents fit. Smaller screens use stacked cards
and natural heights to keep the text readable. All card gaps are 24px.

Lora and Poppins load from Google Fonts, so an internet connection is needed
for those fonts. Georgia and Arial are fallbacks when fonts are unavailable.

The footer uses white Poppins text on a dark blue-gray background, following
the final footer instruction in your request.

TO PUBLISH
Upload index.html, style.css, and script.js to the same directory on your
web host. Include any local project files used by the links. No build step,
framework, or package installation is needed.
