This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
Project Overview
The AI Resume and Portfolio Builder is a modern web application designed to help users create professional resumes and stunning developer portfolios in minutes. By leveraging Artificial Intelligence, the platform automatically generates optimized resume content—such as professional summaries and experience bullet points—and provides a seamless interface to showcase coding projects and technical skills.
Core Features
1. AI-Powered Resume Builder
 * Smart Content Generation: Users input basic details (Job Title, Years of Experience, Key Skills), and the AI generates high-quality, professional summaries and work experience descriptions.
 * Live Preview: Real-time updating of the resume layout as the user types or generates AI content.
 * One-Click PDF Export: A dedicated download feature that instantly converts the finalized resume into a clean, properly formatted PDF document.
2. Dynamic Portfolio Section
 * Interactive Project Grid: A dedicated section where users can seamlessly add multiple projects below their resume.
 * Detail-Rich Project Cards: Each project entry includes fields for the Project Title, Tech Stack (e.g., Next.js, Tailwind CSS, Python), GitHub link, Live Demo link, and an AI-assisted description.
 * State Management: Users can dynamically Add, Edit, or Delete their projects directly from the user interface.
3. Premium User Experience
 * Fully Responsive Design: The layout is highly optimized to look perfect on mobile phones, tablets, and desktop screens.
 * Modern UI/UX: Built with sleek, interactive components and clean color schemes (including customized dark sections like a black background for media viewing).
Recommended Tech Stack
 * Frontend & Routing: Next.js (App Router) and React.
 * Styling: Tailwind CSS for rapid, responsive, and modern UI design.
 * AI Integration: Google Gemini API for fast and intelligent text generation.
 * File Handling: JavaScript Blob and URL object methods (or libraries like html2pdf.js) for smooth image and PDF downloading.
How It Works (The User Flow)
 * Data Entry: The user enters their personal information, skills, and work history into a clean web form.
 * AI Assistance: The user clicks the "Generate with AI" button, triggering the backend API to write professional content based on the raw input.
 * Portfolio Creation: The user scrolls down to the portfolio section, adding their best projects and using the AI to write compelling project descriptions.
 * Review & Export: Once the user is satisfied with the live preview, they simply click the "Download" button to save their complete profile locally.
