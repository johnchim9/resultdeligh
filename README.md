
# School Results Checker

A web application to manage and check student results with Supabase as the backend.

## Features

- Students can check their results by ID and term.
- Teachers can upload results.
- Admin can view all results by term.

## Setup

1. Create a Supabase project.
2. Create a table `results` with columns: `student_id`, `subject`, `score`, `term`.
3. Update `SUPABASE_URL` and `SUPABASE_KEY` in `index.html`.
4. Deploy with GitHub Pages, Netlify, or Vercel.

## Deployment

To deploy on GitHub Pages:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

Enable Pages in repository settings.
