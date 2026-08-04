# Vaishnavi Bhise — Portfolio

AI Engineer | AI & Data Science Student | Generative AI Developer

A personal portfolio site built with React, Vite, and Tailwind CSS — featuring a
terminal-inspired hero with a live neural-network animation, scroll-triggered
skill graphs, and project cards linking straight to GitHub repos.

🔗 **Live site:** _add your Vercel/Netlify URL here once deployed_

---

## Sections

- **Hero** — animated typing effect, neural-network canvas background, profile photo
- **About** — background and focus areas
- **Education** — academic history
- **Skills** — scroll-triggered animated proficiency bars
- **Projects** — 8 projects with real screenshots/photos where available, live repo links
- **Research** — published paper (IJRAR)
- **Experience** — internship timeline
- **Achievements & Certifications** — hackathon wins, verified certificate links
- **Contact** — working contact form (opens your email client)

## Tech stack

- [React](https://react.dev/) + [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/) (core utility classes)
- [lucide-react](https://lucide.dev/) for icons
- Native CSS/Canvas animations (no external animation library)

## Getting started

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal (usually `http://localhost:5173`).

### Build for production

```bash
npm run build
npm run preview
```

## Deployment

This project deploys cleanly to [Vercel](https://vaishnavi-portfolio-inky.vercel.app/) 

## Notes

- The resume PDF and profile/project photos are embedded directly in
  `src/Portfolio.jsx` as base64 data, so downloads and images work
  out of the box with no external hosting needed.
- Update the `GITHUB_URL` and `LINKEDIN_URL` constants near the top of
  `src/Portfolio.jsx` if either profile link ever changes.

---

**Contact:** vaishnavibhise1011@gmail.com · [LinkedIn](https://www.linkedin.com/in/vaishnavi-bhise-26046131b) · [GitHub](https://github.com/VaishnaviBhise05)
