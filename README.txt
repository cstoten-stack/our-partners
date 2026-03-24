Vercel deployment package for the David Doyle Our Partners page.

Files:
- index.html   Main searchable partners page
- vercel.json  Vercel config adding noindex header

Deploy steps:
1. Create a new GitHub repository.
2. Upload both files to the repository root.
3. In Vercel, import the repository as a new project.
4. Framework preset: Other.
5. Leave Root Directory blank.
6. Build Command: leave empty.
7. Output Directory: leave empty.
8. Deploy.

Notes:
- The page already includes a meta robots noindex tag in the HTML head.
- vercel.json also adds X-Robots-Tag: noindex, nofollow to all routes.
