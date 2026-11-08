# Fabian Owuor's portfolio

A responsive, static portfolio site. Open `index.html` in a browser to view it.

## Personalize before publishing

- Update the Education section as your study history changes.
- Revise the featured project cards as your work changes. Projects using private GitHub repositories are described without linking the private source.
- Edit your email or social links in the Contact section if they change.
- The contact form opens a prefilled email draft in the visitor's email app; it does not submit to a server.
- Update or remove the supplied CV at `assets/Fabian-CV.pdf` if you want to publish a different version.
- Add further certificates under `assets/certificates/` and link them from the certificates list in `index.html`.

The CV, certificate PDFs, and profile photo are included in `assets/`.

## Deploy on Vercel

This is a static site and does not need a build step. From this folder, install or run the Vercel CLI, sign in, then deploy the production site:

```powershell
npm install --global vercel
vercel login
vercel --prod
```

Vercel will prompt you to link or create a project and then provide the public URL.
