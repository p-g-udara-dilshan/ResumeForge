# 📄 ResumeForge — ATS-Focused Resume Builder

**A responsive, browser-based resume builder with guided editing, live preview, ATS-oriented feedback, and PDF export.**

[![React](https://img.shields.io/badge/React-UI-149ECA?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Language-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-Build-646CFF?logo=vite&logoColor=white)](https://vite.dev/)
[![Vercel](https://img.shields.io/badge/Vercel-Deployment-000?logo=vercel&logoColor=white)](https://vercel.com/)

### 🔗 [Live Demo](https://resumeforge-ten-peach.vercel.app/) · [Source Repository](https://github.com/p-g-udara-dilshan/ResumeForge)

**Project type:** Personal frontend application · September 2026

## 📖 Overview

ResumeForge is a personal frontend development project designed to simplify professional resume creation. The application offers a **step-by-step resume form**, **multiple layouts**, a **live document preview**, and a **PDF download workflow**, alongside guidance intended to improve resume readability for applicant tracking systems (ATS).

This project explores practical UI engineering problems such as multi-step state management, form validation, local persistence, and rendering user-entered information into downloadable documents.

## 🖼️ Preview

![ResumeForge builder overview](docs/images/resumeforge-overview.jpg)

*Project showcase image with application screens. Some example personal information is illustrative.*

## ✨ Main Features

- **Step-by-step editor:** Resume sections for personal details, education, experience, skills, projects, and other career information
- **Multiple templates:** Alternative resume presentation styles
- **Real-time preview:** Update the document preview as form values change
- **ATS-oriented analysis:** Feedback intended to help improve resume content or formatting
- **PDF export:** Generate and download a resume in PDF format
- **Local autosave:** Save draft data in the user's browser for continuity
- **Validation:** Apply structured validation to form inputs
- **Responsive interface:** Resume editing experience designed for desktop and mobile devices
- **Career profile sections:** GitHub and LinkedIn information within the resume builder

> **ATS limitation:** No scoring rule or template can guarantee acceptance by every applicant tracking system or employer. Feedback should be treated as guidance, not certification of ATS compliance.

## 🛠️ Technology Stack

| Area | Technology |
| --- | --- |
| Frontend | React |
| Language | TypeScript |
| Build tooling | Vite |
| Styling | Tailwind CSS |
| State management | Zustand |
| Forms | React Hook Form |
| Validation | Zod |
| PDF generation | React-PDF |
| Draft persistence | Browser local storage |
| Hosting | Vercel |

## ▶️ Run Locally

For a complete Vite-based source repository:

```bash
git clone https://github.com/p-g-udara-dilshan/ResumeForge.git
cd ResumeForge
npm install
npm run dev
```

Open the local URL shown by Vite. For a production build, use the build script defined in the current `package.json` (commonly `npm run build`).

> These commands reflect the developer-provided Vite technology stack. The exact installed dependencies and scripts should be verified in this repository before following them.

## 🔐 Resume Data & Privacy

Resume content can include personal contact details, employment history, education records, and other sensitive information. If a draft is stored in the browser:

- Avoid using shared/public computers for sensitive resumes.
- Browser storage can be cleared and should not be treated as a permanent backup.
- Do not commit actual user resumes or sample files containing private information.
- Review the implementation before making guarantees about data retention, encryption, or network requests.

## 🧠 Learning Outcomes

- Building reusable React components and guided form flows
- Managing and synchronizing complex application state
- Validating structured user inputs
- Producing PDF documents from frontend data
- Maintaining live previews as forms change
- Creating responsive pages and deploying with Vercel

## 🗺️ Potential Improvements

- [ ] Explain the ATS analysis logic and its limits in the UI
- [ ] Add test cases for forms and generated PDFs
- [ ] Add export/import options for user-owned resume data
- [ ] Improve accessibility and keyboard navigation
- [ ] Expand template customization and print checks

## 👨‍💻 Author

**Udara Dilshan**  
[GitHub](https://github.com/p-g-udara-dilshan) · [LinkedIn](https://www.linkedin.com/in/p-g-udara-dilshan) · [Email](mailto:udara.profile@gmail.com)

---

*ResumeForge is a frontend portfolio application; it does not claim an official ATS endorsement or guaranteed hiring outcomes.*
