# LearnFlow — Design the Future of Learning

A responsive Frontend + UI/UX assignment prototype for turning a long-form document into an interactive online course.

## Assignment coverage

- Upload a document (PDF, DOC, DOCX, TXT) with file picker and drag/drop
- Generate course flow with loading state and success state
- View the generated course
- Navigate through all five lessons
- Mark lessons complete and update progress
- Take a 3-question interactive quiz
- Select answers, move through questions, submit, and receive a score
- Retake the quiz
- Track course progress in a dedicated Progress page
- Responsive desktop, tablet and mobile layouts
- Reusable React components and organized source structure

## Tech stack

React + Vite + JavaScript + CSS + Lucide React icons.

## Run locally

Requirements: Node.js 18+

```bash
npm install
npm run dev
```

Open the Vite URL shown in the terminal, normally `http://localhost:5173`.

## Production build

```bash
npm run build
npm run preview
```

The production output is generated in `dist/` and can be deployed to Vercel, Netlify or GitHub Pages.

## Project structure

```text
learning-future/
├── src/
│   ├── assets/
│   ├── components/
│   ├── hooks/
│   ├── layouts/
│   ├── pages/
│   ├── main.jsx
│   └── styles.css
├── index.html
├── package.json
└── README.md
```

The current prototype keeps the upload and AI generation frontend-only. It simulates course generation after a local document is selected; no external AI/API key is required to demonstrate the assignment workflow.

## Deployment

1. Push this folder to a public GitHub repository.
2. Import the repository into Vercel.
3. Framework: Vite.
4. Build command: `npm run build`.
5. Output directory: `dist`.
