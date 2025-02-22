<div align="center">
  <img src="https://i.ibb.co.com/KzLMNcCB/Screenshot-5.png" height="500" alt="Donate Bangladesh"/>
</div>

# Donate Bangladesh  
A visually appealing and interactive donation platform built entirely with vanilla HTML, CSS, and JavaScript—without any external libraries or frameworks. This project demonstrates how to create a fully functional and professional web application from scratch while focusing on clean design, user experience, and responsive features.

---

## 🚀 Live Demo  
[**Visit Donate Bangladesh**](https://soft-nasturtium-65c914.netlify.app/)

---

## 📋 Table of Contents  
1. [Features](#features)  
2. [Technical Highlights](#technical-highlights)  
3. [Project Structure](#project-structure)  
4. [How to Run](#how-to-run)  
5. [License](#license)  

---

## ✨ Features  

### 1. **Navigation Bar**  
- **Structure**:  
  - Centered logo for branding.  
  - "Blog" button on the left.  
  - Account balance with a coin icon on the right.  
  - "Donation" and "History" buttons in the center for easy navigation.  
- **Sticky Behavior**: The navbar stays fixed at the top, ensuring smooth navigation.  

### 2. **Donation Cards**  
- Three donation cards with the following components:  
  - Image on the left for context.  
  - Donation title and details in the center.  
  - Display of the current donation amount.  
  - Input field to specify a custom donation amount.  
  - "Donate" button to submit the donation.  

### 3. **Donation and History Toggle**  
- **Donation Section**: Shows all available donation cards.  
- **History Section**: Displays transaction history with:  
  - Date and time of each donation.  
  - Donation title and the donated amount.  
- The UI updates dynamically when switching between the "Donation" and "History" tabs.  

### 4. **Donation Functionality**  
- **Real-Time Updates**:  
  - Deducts the donation amount from the account balance.  
  - Updates the card’s current donation amount.  
- **History Log**: Each successful donation is logged in the history section.  
- **Input Validation**:  
  - Prevents donations exceeding the current account balance.  
  - Ensures input is numeric and not empty.  
  - Displays alerts for invalid or empty inputs.  

### 5. **Blog Page (`blog.html`)**  
A dedicated blog page that explains fundamental concepts in web development:  
1. **What is the Document Object Model (DOM)?**  
2. **How to select elements from the DOM?**  
3. **What is event delegation, and why is it useful?**  
4. **How to manipulate an element's attributes and styles using the DOM?**

### 6. **Static Modal for Notifications**  
- A custom modal displays confirmation messages for successful donations, replacing default alert boxes.  

### 7. **Responsive Design**  
- The platform is fully responsive and adapts to various screen sizes for an optimal experience on all devices.  

---

## 🔧 Technical Highlights  

- **Reusable Functions**: Implemented to reduce redundancy and increase efficiency.  
- **Dynamic UI Feedback**: Active status toggles for "Donation" and "History" buttons provide visual feedback to users.  
- **Robust Input Validation**: Prevents invalid or out-of-bounds input, ensuring a smooth user experience.  
- **Responsive Layout**: Ensures compatibility across desktops, tablets, and mobile devices.  

---

## 📁 Project Structure  
├── assets/
│ ├── logo.png
│ └── [additional assets]
├── index.html
├── blog.html
├── styles.css
├── script.js
└── README.md


---

## ⚙️ How to Run  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/smmaksudulhaque2000/Donate-Bangladesh?tab=readme-ov-file

2. Open index.html in your browser to launch the application.

📜 License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project as long as the license terms are met.

💡 Notes
Feel free to replace [<repository-url>](https://github.com/smmaksudulhaque2000/Donate-Bangladesh?tab=readme-ov-file) with the actual URL of your GitHub repository. If you want to expand the README with sections like Contributors, Screenshots, or Troubleshooting, just let me know! 😊