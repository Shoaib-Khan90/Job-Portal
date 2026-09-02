# Careerly — Professional Job Portal

Careerly is a fully responsive frontend job portal developed with React.js, Vite and Tailwind CSS.

## Features

- Professional job-search homepage
- Job title and location search
- Featured jobs and career categories
- Job listing filters
- Complete job details view
- Candidate application form with validation
- Save/favourite jobs using LocalStorage
- Login and registration UI with Candidate/Employer role selection
- Employer dashboard
- Create, update and delete job listings
- Responsive mobile navigation

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

## Deploy on Vercel

Push the source to GitHub and import it into Vercel. Select Vite, use `npm run build` as the build command and `dist` as the output directory.

## Main structure

```text
src/App.jsx    Pages, components and functionality
src/jobs.js    Initial job data
src/index.css  Tailwind and custom responsive design
src/main.jsx   React entry point
```
