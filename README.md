# 🎓 CSE Exam Seating Finder - MUJ

![Project Status](https://img.shields.io/badge/Status-Live-brightgreen)
![University](https://img.shields.io/badge/Manipal%20University-Jaipur-orange)

### 🔗 [Live Demo Link](https://adityasinha-1988.github.io/CSE-Exam-sitting-finder/)

## 📖 Overview
**CSE Exam Seating Finder** is a web-based portal designed to simplify the examination process for students at **Manipal University Jaipur**. Instead of searching through long PDF lists on notice boards, students can simply enter their **Registration Number** and **Course Code** to instantly find their allotted **Room Number** and **Seat Number**.

The unique feature of this project is the **Visual Seat Map**, which highlights the exact location of the student's seat in the exam hall relative to the entry/exit doors.

## ✨ Key Features
* 🔍 **Instant Search:** Fast filtering based on Registration No. & Course Code.
* 🗺️ **Visual Classroom Map:** dynamic generation of the seating layout (5x6 Grid).
* 📍 **Seat Highlighting:** The allocated seat glows Green with a "YOU" marker.
* 🚪 **Accurate Layout:** Visualizes Entry/Exit doors (Left-wall orientation) and Whiteboard position.
* 📱 **Mobile Responsive:** Works perfectly on smartphones and desktops.
* 🧩 **Column-Wise Logic:** Reflects the actual exam filling pattern (Column 1 fills first, then Column 2, etc.).

## 🚀 How It Works
1.  **Data Processing:** Exam data is processed from Excel sheets using a custom **VBA Script** to generate a lightweight JSON dataset (`student_data.js`).
2.  **Frontend Logic:** The web interface reads this data and matches the student's input.
3.  **Visualization:** JavaScript dynamically renders the classroom grid and highlights the specific seat coordinates (e.g., R2-C3).

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Animations & Grid Layout), JavaScript (ES6).
* **Data Handling:** Excel VBA (for JSON generation).
* **Hosting:** GitHub Pages.

## 📸 Screenshots
SS.JPG
## 👨‍💻 Developed By
**Aditya Sinha**
* Department of Computer Science & Engineering
* Manipal University Jaipur

---
<p align="center">
  Made with ❤️ for MUJ Students
</p>
