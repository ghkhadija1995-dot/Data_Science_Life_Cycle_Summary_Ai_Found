# Data Science Study Guide & Life Cycle Summary

An essential, high-level summary covering foundational data science concepts, statistical principles, machine learning, big data architectures, and the end-to-end 10-step Data Science Life Cycle. Designed as a clean reference for students, researchers, and practitioners.

---

## 📄 Included Files

- **`Data_Science_Life_Cycle_Summary.pdf`**: The primary published reference document containing the full structured guide.
- **`summary.html`**: The HTML/CSS source template used to render and compile the PDF via WeasyPrint.
- **`README.md`**: Project documentation, version history, and compilation instructions.

---

## 🤖 AI Tools Used

- **Claude** (Anthropic)
- **Gemini** (Google)

---

## 💬 Dialogue & Iterative Development History

This document was created and refined through a series of iterative prompt requests:

### Prompt 1 (Anonymization Cleanup)
> *"All persona references inside the original commentary have been anonymized (e.g., Professor A, Dr. B) to maintain a purely academic focus. remove this sentence"*
- **Action Taken**: Removed the metadata note regarding persona anonymization from the body summary text.

### Prompt 2 (Header Removal)
> *"Prepared by: Professor A & Dr. B • Academic Reference • 2026 Edition remove this sentence also"*
- **Action Taken**: Removed the top header metadata bar from the document layout.

### Prompt 3 (User Confirmation)
> *"good"*
- **Action Taken**: Finalized document structure.

### Prompt 4 (Title Styling)
> *"can you change the color of the title to be black"*
- **Action Taken**: Updated CSS styles to set the title text color (`<h1>`) to `#000000` (black).

### Prompt 5 (AI Tool Attribution)
> *"the AI tools used cloude and gemini"*
- **Action Taken**: Added an AI Tools section acknowledging Claude and Gemini.

### Prompt 6 (File Reference Inclusion)
> *"montion it in the file"*
- **Action Taken**: Explicitly documented all associated project files inside the `README.md` file.

---

## 🛠️ Build & Compilation

The PDF is generated programmatically using Python and **WeasyPrint** from the source HTML/CSS:

```bash
python -c "from weasyprint import HTML; HTML('summary.html').write_pdf('Data_Science_Life_Cycle_Summary.pdf')"
```
