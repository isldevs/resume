# LaTeX CV – Sivlay Yi

This repository contains the LaTeX source files for my professional resume/CV, highlighting my experience as a **Backend Developer (Java & Spring Boot)**.

---

## 📌 Project Overview

The CV template includes:

- Education  
- Work Experience  
- Projects (personal and internal for Cam Info Services)  
- Technical Skills  
- Online Presence / Social Media  

It is designed with a **modern LaTeX layout** that is clean, ATS-friendly, and print-ready.

---

## 🛠 Requirements

To build and view the PDF version of the resume, you need:

- A LaTeX distribution installed locally (e.g., TeX Live, MikTeX) **or** use an online editor like [Crixet](https://app.crixet.com).  
- Required packages:
  - `latexsym`, `fullpage`, `titlesec`, `marvosym`, `enumitem`, `hyperref`, `fancyhdr`, `tabularx`, `fontawesome5`, `multicol`  
- Internet connection for hyperlinks (optional, for online social links).

---

## ⚡ How to Use

### 1. Using Crixet (Online)
1. Go to [Crixet](https://app.crixet.com).  
2. Create a new project and upload all `.tex` files (e.g., `main.tex`) and supporting files (e.g., `glyphtounicode.tex`).  
3. Click **Compile** to generate the PDF.  
4. Download the PDF for sharing or printing.

### 2. Using Local LaTeX Environment
1. Clone or download the repository.  
2. Make sure all required LaTeX packages are installed.  
3. Open the main `.tex` file in a LaTeX editor (e.g., TeXstudio, Overleaf, VS Code with LaTeX Workshop).  
4. Compile using **PDFLaTeX**.  
5. Check the output PDF in the default location.

---

## ✏️ Customization

You can update your CV easily:

- **Personal Information & Contact:** Edit the `\begin{center}` section in `main.tex`.  
- **Education:** Update the `\resumeSubheading` blocks.  
- **Work Experience:** Add, remove, or edit `\resumeSubheading` and `\resumeItem` entries.  
- **Projects:** Add new projects with `\resumeProjectHeading` and `\resumeItem`.  
- **Skills:** Update the `\section{Technical Skills}` block.  
- **Online Presence:** Add social links using `\fa...` icons from `fontawesome5`.

---

## 📁 Folder Structure

