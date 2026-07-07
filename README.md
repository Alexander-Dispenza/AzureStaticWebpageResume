# Alexander Dispenza Resume Website

This is a static resume website designed for Azure Static Web Apps.

## Files

- `index.html` - Main website page
- `assets/style.css` - Website styling
- `assets/script.js` - Mobile navigation and scroll animation
- `resume.pdf` - Put your resume PDF in the root folder with this exact name

## How to use with Azure Static Web Apps

1. Create a new GitHub repository, for example `alexander-resume-site`.
2. Upload these files to the repository.
3. Add your resume PDF to the root of the project and name it `resume.pdf`.
4. In Azure Portal, create a new Static Web App.
5. Connect it to your GitHub repository.
6. For build settings, use:
   - App location: `/`
   - Output location: leave blank
   - API location: leave blank
7. Deploy.
8. Add your custom domain in the Azure Static Web App settings.
9. Add the DNS records Azure gives you at your DNS provider, such as Cloudflare.

## Editing content

Most of the content is inside `index.html`.

Common things to change:

- Page title
- Hero summary
- Experience bullet points
- Project cards
- Certifications
- Email/contact links

## Resume PDF

The buttons currently link to:

```text
resume.pdf
```

Place your resume PDF in the same folder as `index.html` and name it exactly:

```text
resume.pdf
```
