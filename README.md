# Injamamul Haque — Online & 1-Page ATS-Friendly Resumes

Online, shareable, and print-ready **1-Page A4** resumes built with **HTML5** and **Tailwind CSS v4 Play CDN** (`@tailwindcss/browser@4`). Each version is tailored for a specific engineering role and optimized for both **ATS (Applicant Tracking Systems)** and **1-page PDF printing**.

---

## 🔗 Live Resume Links & Ready-to-Use PDFs

| Role Variant | 🌐 Live Web Version (GitHub Pages) | 📄 1-Page A4 PDF Download | HTML Source |
| :--- | :--- | :--- | :--- |
| **Frontend Engineer** | [ih-rul.github.io/resume/](https://ih-rul.github.io/resume/) | [Injamamul_Haque_Resume.pdf](./Injamamul_Haque_Resume.pdf) | [`index.html`](./index.html) |
| **Full-Stack Engineer** | [ih-rul.github.io/resume/full-stack](https://ih-rul.github.io/resume/full-stack) | [Injamamul_Haque_FullStack_Resume.pdf](./Injamamul_Haque_FullStack_Resume.pdf) | [`full-stack/index.html`](./full-stack/index.html) |
| **Software Engineer** | [ih-rul.github.io/resume/software-engineer](https://ih-rul.github.io/resume/software-engineer) | [Injamamul_Haque_Software_Engineer_Resume.pdf](./Injamamul_Haque_Software_Engineer_Resume.pdf) | [`software-engineer/index.html`](./software-engineer/index.html) |
| **AI Software Engineer** | [ih-rul.github.io/resume/ai-engineer](https://ih-rul.github.io/resume/ai-engineer) | [Injamamul_Haque_AI_Engineer_Resume.pdf](./Injamamul_Haque_AI_Engineer_Resume.pdf) | [`ai-engineer/index.html`](./ai-engineer/index.html) |
| **Custom (JD-Tailored)** | [ih-rul.github.io/resume/custom](https://ih-rul.github.io/resume/custom) | [Injamamul_Haque_Custom_Resume.pdf](./Injamamul_Haque_Custom_Resume.pdf) | [`custom/index.html`](./custom/index.html) |

---

## ✨ Key Features

- **Zero-Build Setup:** Powered by Tailwind CSS v4 Play CDN (`https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4`) and Google Fonts (`Inter`). Open any `index.html` file directly in the browser.
- **100% ATS-Friendly Structure:** Single-column semantic HTML (`<header>`, `<main>`, `<section>`), clean typography hierarchy, explicit clickable profile URLs, and contextual keyword placement across experience bullets.
- **Strict 1-Page A4 Print Layout:** Custom `@media print` and `@page { size: A4 portrait; margin: 9mm 12mm; }` rules ensure that clicking **Print / Save PDF** (`Ctrl + P`) generates a crisp, single-page A4 PDF with the top navigation bar automatically hidden (`print:hidden`).
- **Role Switcher & Share Toolbar:** Sticky top bar in web view allows instant switching between all 4 role variants and one-click link copying.

---

## 🛠️ Local Usage & PDF Generation

### 1. Preview in Browser
Simply open [`index.html`](./index.html) in any browser, or serve locally:

```bash
npx serve .
```

### 2. Save as PDF via Browser
1. Open the desired resume page in Chrome/Edge.
2. Click the **Print / Save PDF** button in the top-right bar (or press `Ctrl + P` / `Cmd + P`).
3. Set **Destination** to `Save as PDF`, **Paper size** to `A4`, and uncheck **Headers and footers**.

### 3. Regenerate All 4 PDFs via Headless Chrome CLI
```bash
google-chrome --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=Injamamul_Haque_Resume.pdf file://$(pwd)/index.html
google-chrome --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=Injamamul_Haque_FullStack_Resume.pdf file://$(pwd)/full-stack/index.html
google-chrome --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=Injamamul_Haque_Software_Engineer_Resume.pdf file://$(pwd)/software-engineer/index.html
google-chrome --headless --disable-gpu --no-pdf-header-footer --print-to-pdf=Injamamul_Haque_AI_Engineer_Resume.pdf file://$(pwd)/ai-engineer/index.html
```

---

## 👤 Contact

- **Name:** Injamamul Haque
- **Email:** [injam.cse@gmail.com](mailto:injam.cse@gmail.com)
- **LinkedIn:** [linkedin.com/in/meinjam](https://linkedin.com/in/meinjam)
- **GitHub:** [github.com/meinjam](https://github.com/meinjam)
- **Portfolio:** [injam.netlify.app](https://injam.netlify.app/)

