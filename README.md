# 📄 CV Formatting Automation Tool - Enterprise Showcase

> **🔒 Proprietary Code Notice:** This tool was built for Mindworx Academy to solve an internal operational bottleneck. The source code is private to protect the organization's data. This repository serves as a technical case study of the architecture and automation logic.

## 📌 The Business Problem
The recruitment and placement teams at Mindworx were spending hours manually reformatting candidate CVs. Consultants had to open Word documents, copy-paste text, fix layouts, and ensure everything matched the strict corporate branding before sending them to partner employers. This was highly inefficient and prone to formatting errors.

## 💡 The Solution
I developed an automated processing tool that dramatically reduced the time consultants spent on manual formatting. The system accepts Word and PDF documents, extracts the core professional data, and maps it dynamically into the official Mindworx corporate template.

## ⚙️ How It Works
1. **Upload:** The user uploads a raw PDF or Word CV via a clean web interface.
2. **Extraction:** The backend Python logic parses the document, extracting key data points (name, contact info, experience, education).
3. **Mapping:** The extracted data is mapped into a pre-defined JSON structure.
4. **Generation:** The system uses `python-docx` to inject the parsed data into the official corporate Word template, ensuring 100% formatting accuracy.
5. **Preview & Export:** The user can preview the formatted CV in real-time and download the final document.

## 📈 Impact & Results
- **90% Time Reduction:** Automated over 100+ CVs weekly, reducing the formatting time by ~90%.
- **Zero Formatting Errors:** Eliminated human error in layout and branding.
- **Scalability:** Allowed the placement team to process a high volume of candidates during peak recruitment drives without increasing headcount.

## 🧠 Technical Decisions & Trade-offs
- **Why Python & Flask?** Python has excellent libraries for document parsing (`PyPDF2`, `python-docx`). Flask was chosen to keep the application lightweight and easy to integrate into the existing Mindworx internal network.
- **Real-time Preview:** Implemented a JavaScript-based real-time preview using `mammoth.js` (or similar) so consultants could see exactly what the final document would look like before committing to the export.

## 💻 Tech Stack
- **Backend:** Python, Flask, REST APIs
- **Frontend:** HTML, CSS, JavaScript
- **Document Handling:** `python-docx`, `PyPDF2` (or equivalent parsing library)
- **Database:** SQLite (for logging processed files)

## 👨‍💻 My Role
- **Full-Stack Development:** Built both the backend document-parsing logic and the frontend user interface.
- **Problem Solving:** Designed the algorithm that handles messy, inconsistent CV formats and standardizes them.
- **Deployment:** Deployed the tool locally for the Mindworx team to use securely.

## 📸 System Interface (Anonymized)
*(Drag and drop 3 screenshots of the UI here. Make sure to use fake data like "John Doe")*
