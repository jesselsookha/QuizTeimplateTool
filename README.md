
# Brightspace (Arc) Quiz Creation Workbook (Excel)

This Excel-based tool helps lecturers quickly create quiz question banks compatible with **Arc _(Brightspace D2L)_** using **CSV import**. Designed around **Question Library** formatting rules, the workbook allows you to build quizzes using structured templates, drop-down lists, and contextual help — all within a user-friendly Excel environment.

### Author 
[Jessel Sookha](https://github.com/jesselsookha)

📥 **[Click here to download the Brightspace (Arc) Quiz Creation Workbook (Excel .xlsm)](https://github.com/jesselsookha/QuizTemplateTool/raw/refs/heads/main/QuizTemplatevTool.xlsm)**  
---
## 📘 Overview

This workbook allows you to:
- Build Brightspace-compatible CSV question files using preformatted Excel templates.
- Choose from supported question types: True/False, Multiple Choice, Multi-Select, Matching, Ordering, and more.
- Export your quiz sheets as CSV (UTF-8), ready for upload to Arc _(Brightspace)_.
- Use drop-downs and built-in macros to manage question formatting with ease.
- View detailed guidance, tips, and field explanations in-sheet.

---

## 🚀 Getting Started

1. **Download** the latest `.xlsm` file from this repository. **(link shared above)**
2. **Enable Macros** when prompted (this is required for buttons to work).
3. Open the workbook and go to the `empty` sheet.
4. Click the large **"Add New Quiz Sheet"** button to begin creating your quiz.
5. In your new sheet (e.g., `quiz1`, `lu1_theme1`), click cell A1 and use the **+** button to insert a question template.
6. Fill in the fields in Column B. Click **?** for contextual help as needed.
7. When done, copy Columns A–E into a new workbook and save as **CSV UTF-8**.
8. Upload the CSV file to Brightspace using the **Import** tool in the **Question Library**.

---

## 🧩 Workbook Structure

| Sheet Name     | Purpose |
|----------------|---------|
| `how to`       | Front page guide for using the tool. |
| `quest types`  | Details all supported Brightspace question types, including use cases and time estimates. |
| `field guide`  | Explains the meaning and use of each CSV field (column), including required values. |
| `sample`       | Raw CSV data exported from Brightspace, for comparison/reference. |
| `empty`        | Source of all available templates. Includes the **Add New Quiz Sheet** button. |
| `quiz_template`| Pre-formatted empty layout with buttons for inserting, deleting, or getting help on questions. |
| `quiz`, `quiz1`| User-generated sheets that contain your quiz content and inserted question templates. |

---

## 📝 Notes & Tips

- **Only edit the `quiz`, `quiz1`, etc. sheets.** Avoid modifying `quiz_template`, `empty`, or helper sheets unless you're customizing.
- Use drop-downs for fields like **Scoring** and **Difficulty** to ensure valid entries.
- Always **Save your work** before exporting to prevent macro-related data loss.
- Leave a blank row between questions for readability (the template questions already contain a blank row).
- If a sheet breaks, copy a fresh one from `quiz_template`.

---

## 📂 Exporting & Uploading

To upload to Arc _Brightspace_:
1. Copy the relevant rows (A to E) from your quiz sheet.
2. Paste into a new workbook.
3. Save that file as **CSV UTF-8**.
4. Import into Brightspace using the **Upload File** option in the Question Library.

---

## 🙌 Contributing

Contributions, ideas, and improvements are welcome! Please:
- Submit issues or feature requests via the **Issues** tab.
- Fork the repository and submit a pull request if you'd like to improve the tool.
- Reach out in person or via email/chat if you're part of our academic team.

---

## 🔒 Disclaimer

This tool is not affiliated with or officially supported by Brightspace/D2L. It was developed to streamline internal workflow for academic staff using Arc _(Brightspace D2L)_ at the IIE Varsity College.

---

## 📎 License

Released under the MIT License. Feel free to reuse, adapt, and enhance with credit.

## 📚 References

Dr. Jennifer Lynn Wagner. D2L Brightspace Tips: Sample Question Import CSV File. [online]. Available at: <https://jenniferlynnwagner.com/d2l-question-import.html> [Accessed 24 April 2025].

D2L Knowledge, 2025. Import questions into the Question Library. [online]. Available at: <https://community.d2l.com/brightspace/kb/articles/3411-import-questions-into-the-question-library> [Accessed 1 May 2025].

D2L Knowledge, 2025. Creating Question Library questions. [online]. Available at: <https://community.d2l.com/brightspace/kb/articles/3410-creating-question-library-questions> [Accessed 1 May 2025].

OpenAI, 2025. ChatGPT – AI-powered assistance for development and documentation. [online]. Available at: <https://openai.com/chatgpt> [Accessed 5 May 2025].
