Resume.io - Professional Resume Builder
🚀 Introduction
Resume.io is a powerful, client-side resume builder designed to help users create, customize, and export professional resumes with ease. Built entirely with HTML, CSS, and JavaScript, this application runs directly in the browser, offering a real-time editing experience without the need for a backend server. User data is securely saved in the browser's local storage, ensuring that work is never lost between sessions.

This project evolved from a simple resume form into a feature-rich application with multiple templates, dynamic sections, image editing, and robust export capabilities.

✨ Key Features
Real-Time Preview: See your resume update instantly as you type.

Multiple Professional Templates: Choose from 8 distinct, professionally designed templates to match your industry and personal style:

Modern

Corporate

Creative

Technical

Minimalist

Executive

Academic CV

Bold

Dynamic Sections: Easily add or remove multiple entries for:

Work Experience

Projects

Education

Certifications

Awards

Languages

Image Cropping: Upload a profile picture and use the integrated cropping tool to get the perfect headshot for your resume.

Export to Word (.docx): Download your final resume as a high-quality, readable Microsoft Word document. The filename is automatically generated based on the candidate's name.

Local Storage Persistence: All your data is automatically saved to your browser's local storage, so you can close the tab and return to your work at any time.

Quick Select Options: Speed up data entry by selecting common skills and languages from pre-populated lists.

Fully Client-Side: The entire application runs in the browser. No server-side processing is required, ensuring privacy and speed.

Clean, Modern UI: A user-friendly interface with collapsible sections makes editing your resume a seamless experience.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS for rapid UI development.

Icons: Lucide Icons for clean and modern vector icons.

Image Cropping: Cropper.js for the interactive image cropping functionality.

Word Export: html-docx-js for converting the HTML preview into a downloadable .docx file.

🚀 How to Use
Open the index.html file in any modern web browser.

Fill in your details in the editor panel on the left. Start with "Personal Information" and work your way down through the collapsible sections.

Add dynamic entries by clicking the "Add..." button in sections like Work Experience, Projects, etc. You can remove any entry by clicking the × button.

Upload a photo (optional) in the "Personal Information" section. Use the cropping tool to adjust your picture.

Select a template from the switcher at the top of the preview panel on the right. Your preview will update instantly.

Review your resume in the live preview panel.

Export your resume by clicking the "Export to Word" button. A .docx file named after you will be downloaded.

💡 Future Improvements
Theme Customization: Allow users to select a primary accent color for their chosen template.

Drag-and-Drop Reordering: Implement functionality to reorder entries within a section (e.g., move one job experience above another).

AI-Powered Suggestions: Re-integrate an optional AI feature (with user consent and an API key field) to provide suggestions for summaries or job descriptions.

More Export Formats: Add options to export as JSON (for data backup) or PDF.
