A sleek, interactive web application featuring a dark-themed gradient UI with glassmorphism effects, designed for a clean and modern user experience. This project showcases smooth animations, responsive form elements, and a cohesive color scheme that enhances readability while maintaining visual appeal.

Key Features
✅ Elegant Dark Gradient Background – Smooth transition from deep navy (#0f2027) to teal (#2c5364) for a professional look.
✅ Glassmorphism Design – Frosted glass effects on inputs and containers (backdrop-filter: blur()).
✅ Interactive Form Elements – Stylish text areas, dropdowns, and buttons with hover/focus animations.
✅ Custom UI Components – Enhanced <select> dropdown with SVG arrow, subtle shadows, and rounded corners.
✅ Responsive Layout – Centered flexbox design that works on all screen sizes.
✅ Modern Aesthetic – Cyan/teal accent colors (#00c6ff, #0072ff) with smooth transitions.

Tech Stack
HTML5 – Semantic structure

CSS3 – Flexbox, gradients, custom scrollbars, and animations

Glassmorphism – Semi-transparent UI elements with blur effects

Use Cases
Data Dashboards – Clean display for analytics or visualization

Web Applications – Forms, settings panels, or admin interfaces

Portfolio Projects – Showcases modern CSS techniques

Why This Design?
Dark Mode Friendly – Reduces eye strain with dark backgrounds and soft accent colors.

Visual Hierarchy – Clear contrast between interactive elements and background.

Smooth Animations – Hover effects and transitions for better user engagement.

Preview
UI Preview (Example: Replace with actual screenshot)

Try it out! The UI is optimized for both desktop and mobile viewing.

Would you like any modifications, such as a light theme or different accent colors? 🎨

PROJECT NAME IS TEXT TO SPEECH
script.js
JS 1.18KB
style.css
CSS 1.22KB
index.html
HTML 511B
ANALYZE AND GIVE ME DESCRIPTION FOR THISS PROJECT
Project Description: Text-to-Speech (TTS) Converter with Voice Selection
A web-based Text-to-Speech (TTS) application that converts user-input text into spoken audio using the browser's built-in Web Speech API. This project allows users to select from multiple available voices (system-dependent) and customize their listening experience.

Key Features
✅ Text-to-Speech Conversion – Converts written text into spoken words using SpeechSynthesisUtterance.
✅ Multi-Voice Support – Dynamically loads available system voices (male/female, different languages).
✅ Responsive UI – Clean, centered layout with smooth transitions and focus states.
✅ Custom Voice Selection – Dropdown menu populated with available voices (e.g., "Google US English," "Microsoft Zira").
✅ Modern Styling – Gradient background, rounded corners, and subtle shadows for a polished look.

Tech Stack
Frontend:

HTML5 – Structure for text input, dropdown, and button.

CSS3 – Flexbox layout, gradient background, and hover effects.

JavaScript (Web Speech API) – Powers speech synthesis and voice selection.

How It Works
User Input:

Types/pastes text into the <textarea>.

Voice Selection:

Chooses a preferred voice from the dropdown (auto-populated via speechSynthesis.getVoices()).

Speech Generation:

Clicking "Speak" triggers textToSpeech(), which converts text to audio using the selected voice.

Code Breakdown
index.html
Contains a textarea (for input), dropdown (voice selection), and button (to trigger speech).

Linked to style.css (styling) and script.js (functionality).

style.css
Gradient Background (#d3c0a0 to #5c5b5b) for a warm, neutral aesthetic.

Consistent Styling – Rounded borders, box shadows, and hover effects on interactive elements.

Responsive Centering – Uses flexbox to align content vertically and horizontally.

script.js
populateVoiceList() – Fetches available voices and updates the dropdown.

textToSpeech() – Converts text to speech using the selected voice.

Event Handling – Automatically loads voices when the page initializes (onvoiceschanged).

Possible Use Cases
Accessibility Tool – Helps visually impaired users hear written content.

Language Learning – Listen to pronunciation in different accents/languages.

Proofreading Assistant – Hear written text to catch errors.

Voice-Enabled Apps – Can be extended for chatbots, narrations, or voice assistants.

Screenshot Preview

!WORKING](https://github.com/user-attachments/assets/babc83fb-62bc-4d36-b3b4-531441f018ab)

Future Enhancements
🔹 Volume/Pitch Control – Add sliders to adjust speech parameters.
🔹 Download Audio – Save speech as an MP3/WAV file.
🔹 Dark/Light Mode Toggle – Improve accessibility.
🔹 Multi-Language Support – Auto-detect language and suggest voices.

