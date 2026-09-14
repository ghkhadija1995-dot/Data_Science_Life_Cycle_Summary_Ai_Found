### 🔗 Training Program

This project was completed as part of the L0-FAE — AI Fundamentals for the Workplace training program at SDAIA Academy, under the supervision of Abdullah Khalid AlShahrani.

The portfolio demonstrates the practical application of AI fundamentals in the workplace through prompt engineering, professional writing, information processing, verification and fact-checking, safe and responsible use, and daily task integration.

Official SDAIA Academy GitHub:  
https://github.com/SDAIAAcademy
———————

💡 1. The Concept:
This project is an essential, high-level reference study guide custom-designed for students, researchers, and data science practitioners. It aims to break down complex theoretical frameworks into a clean, easy-to-read, and highly scannable bullet-point format.

Key Highlights of the Guide:
* Core Concepts: Quick reference summaries covering foundational statistics, machine learning principles, and big data architectures.
* The 10-Step Life Cycle: A step-by-step breakdown explaining the end-to-end data science pipeline in short, simple sentences.
* Academic Neutrality: Fully anonymized text using placeholders (e.g., Professor A, Dr. B) to keep the focus strictly on academic value and remove personal metadata.

⚙️ 2. How to Run and Use
This project was developed using a template-to-print workflow, making it very easy to read, modify, and recompile:

1. Reading the Guide:
* Open Data_Science_Life_Cycle_Summary.pdf using any modern web browser or PDF reader to access the final, polished document.

2. Modifying the Design & Content:
    * To change styles (such as the recent update that changed the title to black) or text contents, open the summary.html source template in a code editor (like VS Code or Notepad).
    * Locate the main title tag and edit its CSS color property to #000000 (black).

3. Compiling back to PDF:
    * Once you save your changes in the HTML/CSS code, use a command-line print tool like WeasyPrint to render and export the code back into a beautifully formatted, print-ready PDF file.

🛠️ 3. Technical Documentation

A. Included Files
* Data_Science_Life_Cycle_Summary.pdf: The primary published reference document containing the full structured guide.
* summary.html: The HTML/CSS source template used to control the visual structure, fonts, and print layout.

B. Tech Stack & AI Tools
* Claude (Anthropic) & Gemini (Google): The primary AI engines used to summarize the original text, structure the lifecycle steps, write the clean code, and refine the text through iterative prompt updates.
* WeasyPrint: The technical compilation engine used to convert HTML and CSS code directly into a standard PDF asset.

C. Iterative Development History (The 5 Prompts)
The final document structure was achieved through a multi-step prompt engineering process:

* Prompt 1 (Initial Generation): Extracted the core data science topics into short bullet points and framed the 10 life cycle steps using anonymous personas (e.g., Professor A).
* Prompt 2 (Anonymization Cleanup): Removed a metadata sentence that explicitly pointed out that the personas were anonymized, ensuring a cleaner look.
* Prompt 3 (Header Removal): Removed the top metadata bar containing the date and preparation text to simplify the page layout.
* Prompt 4 (User Confirmation): Confirmed the basic layout structure was correct.
* Prompt 5 (Title Styling): Updated the CSS script to change the header text color to full black (#000000) for sharper contrast and readability.

D. Development Metrics
* Total Execution Time: Approximately 2 hours (covering prompt iterations, CSS adjustments, and WeasyPrint compiling tests).
  
* Document Length Constraints: Kept strictly under a maximum of 5 pages to maintain a concise, quick-study layout.
