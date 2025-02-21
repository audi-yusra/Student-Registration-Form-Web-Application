# Student Registration Form Web Application


Welcome to the **Student Registration Form** project! This is a sleek, user-friendly, and responsive web application designed to collect and display student information effortlessly. Whether you're managing student data for a school, college, or any educational institution, this form simplifies the process with its intuitive design and dynamic functionality.

---

## 📌 **Table of Contents**
1. [Project Overview](#-project-overview)
2. [Features](#-features)
3. [How It Works](#-how-it-works)
4. [Technologies Used](#-technologies-used)
5. [Installation](#-installation)
6. [Usage](#-usage)

---

## 🚀 **Project Overview**

The **Student Registration Form** is a web application built using **HTML**, **CSS**, and **JavaScript**. It allows users to input student details such as **name**, **gender**, **course**, **email**, **skills**, and an optional **image**. Upon submission, the entered data is dynamically displayed in a neatly formatted section on the same page. The form is fully responsive, ensuring a seamless experience across all devices.

---

## ✨ **Features**

- **User-Friendly Form**: A clean and intuitive interface for collecting student details.
- **Dynamic Data Display**: Submitted data is displayed instantly in a structured format.
- **Image Upload**: Option to upload a student's image for a personalized touch.
- **Responsive Design**: Works flawlessly on desktops, tablets, and mobile devices.
- **Form Validation**: Ensures required fields are filled out before submission.
- **Skills Selection**: Allows students to select their skills using checkboxes.

---

## 🛠 **How It Works**

### **HTML Structure**
The `index.html` file defines the structure of the form and the display section. Key components include:
- Input fields for **name**, **course**, **email**, and **image upload**.
- Checkboxes for **gender** and **skills** selection.
- A **submit button** to process the form data.

```html
<form action="" id="form">
    <div class="f1">
        <label for="name">Name*:</label>
        <input type="text" name="name" class="in" placeholder="Enter name" required>
    </div>
    <div class="f2">
        <label for="gender">Gender:</label>
        <div class="c">
            <div class="c1"><input type="checkbox" name="gender">
                <label for="">Male</label>
            </div>
            <div class="c1"><input type="checkbox" name="gender">
                <label for="">Female</label>
            </div>
        </div>
    </div>
    <!-- Additional fields for course, email, skills, and image upload -->
</form>
```

### **JavaScript Functionality**
The `script.js` file handles form submission and dynamically displays the entered data:
- Prevents the default form submission behavior.
- Captures input values and creates new DOM elements to display the data.
- Handles image uploads and displays the uploaded image.

```javascript
form.addEventListener("submit", (e) => {
    e.preventDefault();
    data();
    form.reset();
});
```

### **CSS Styling**
The `style.css` file provides the visual styling for the form and the displayed data:
- Modern and clean design with a dark theme.
- Responsive layout adjustments for smaller screens.

```css
.container {
    background-color: #1f1f1f;
    border-radius: 5px;
    box-shadow: 0 0 15px black;
    padding: 20px;
}
```

---

## 💻 **Technologies Used**

- **HTML**: For structuring the form and display section.
- **CSS**: For styling the form and ensuring responsiveness.
- **JavaScript**: For handling form submission and dynamic data display.

---

## 📥 **Installation**

To use this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/student-registration-form.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd student-registration-form
   ```

3. **Open the Project**:
   - Open the `index.html` file in your preferred browser.

---

## 🖥 **Usage**

1. **Fill Out the Form**:
   - Enter the student's **name**, select **gender**, **course**, **email**, and upload an **image** (optional).
   - Select the student's **skills** from the provided checkboxes.

2. **Submit the Form**:
   - Click the **Submit** button to process the data.

3. **View the Displayed Data**:
   - The submitted data will be displayed in the **Registered Students** section below the form.

---
