# Online-Payment-Fraud-Detection
A Real time fraud detection system which detects the frauds in the real world scenario
🎨 UI Walkthrough – Online Payment Fraud Detection
🏠 Home Page Overview

"The user starts here – simple interface with clear call-to-action"

Clean, minimalistic layout for clarity and ease of navigation

Subtle background image for a modern look without distractions

Central “Start Assessment” button as the clear entry point

Intuitive workflow so users know exactly what to do next

<img width="1094" height="632" alt="image" src="https://github.com/user-attachments/assets/16de8f6b-6bff-4984-86bb-d4bec83e0c01" />


📝 Form Page Details

"Users enter transaction details – all fields are validated"

Input fields for Sender ID, Receiver ID, Amount, Location, Time

Dropdown menu for transaction type (Purchase, Transfer, Withdrawal)

Real-time validation ensures all required fields are filled correctly

Fully responsive design adapts beautifully across devices

(Demo tip: resize browser window to showcase responsiveness)

<img width="1092" height="619" alt="image" src="https://github.com/user-attachments/assets/d22f1c11-5e0a-4151-bafd-67240ed51b88" />


📊 Results Page Features

"Visual risk assessment with color coding"

Fraudulent transactions → red pulse animation ⚠️ grabs attention instantly

Safe transactions → green checkmark ✅ reassures user quickly

Probability meter animation displays fraud likelihood (e.g., 87% risky)

Smooth transitions for easy interpretation with minimal cognitive load

💻 Key JavaScript Snippet
// Navigation between pages
function showPage(page) {
  // Hide all pages first
  document.querySelectorAll('.page-container').forEach(p => p.style.display = 'none');
  // Show requested page
  page.style.display = 'block';
}


Enables seamless SPA navigation (single-page app)

Hides irrelevant sections and displays only the active one

Improves speed and user experience by avoiding reloads

<img width="1108" height="630" alt="image" src="https://github.com/user-attachments/assets/6c663118-079f-4e60-9aaa-5c0978bb939a" />


🎬 Demo Notes

Animation demo: highlight red pulse & green check transitions

Responsive design mockup: resize browser for adaptive layout

Full code walkthrough: showcase FastAPI backend + JS-driven UI
