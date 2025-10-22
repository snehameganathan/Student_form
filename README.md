# 🧾 Student Form

A simple and interactive **Student Form** web application built using **HTML**, **CSS**, and **JavaScript**.  
This project allows users to input student details, validates the form fields, and displays the submitted information in a table. It also includes real-time validation and deletion functionality.

---

## 🌐 Live Demo

👉 **[Click Here to View the Live Demo](https://snehameganathan.github.io/Student_form/)**  
*(Replace the above link with your GitHub Pages or hosting URL once deployed.)*

---

## 🚀 Features

✅ **Form Validation** – Ensures that the name, email, and password fields meet specific criteria before submission.  
✅ **Dynamic Table Update** – Displays student details in a table immediately after submission.  
✅ **Delete Functionality** – Allows the user to remove specific entries from the table.  
✅ **Submit Button Control** – Disabled until all required fields are valid.  
✅ **Responsive Design** – The form layout is centered and adjusts nicely to various screen sizes.

---

## 🧩 Technologies Used

- **HTML5** – For creating the structure of the form and table  
- **CSS3** – For styling the layout and making it user-friendly  
- **JavaScript (ES6)** – For validation and dynamic DOM manipulation  

---

## 📋 Form Fields

| Field Name | Type | Description | Validation |
|-------------|------|-------------|-------------|
| Name | Text | Student’s name | Cannot be empty |
| Age | Number | Student’s age | Required field |
| Gender | Radio Button | Select Male or Female | Optional |
| Course | Dropdown | Choose from JavaScript, HTML, CSS, Java, Python, React JS | Optional |
| E-mail | Email | Student’s email address | Must follow standard email format |
| Password | Password | Secure password | Minimum 6 characters |

---

## ⚙️ Functionality

### 🔹 Validation Rules
- **Name** must not be empty.  
- **Email** must follow a valid format (e.g., `example@gmail.com`).  
- **Password** must be **at least 6 characters long**.  
- The **Save** button remains disabled until all validations are satisfied.

### 🔹 Table Management
- On form submission, the details are added to the table below.  
- Each record includes a **Delete** button to remove that specific row.

---
