
# Next Build Fix Pack

This is a known-good minimal Next.js project that builds on Vercel.

## How to use
1. Download this zip.
2. Replace the contents of your GitHub repo (or set Vercel Root Directory) so that at **repo root** you have:
   - package.json
   - pages/
   - next.config.mjs (optional)

3. On Vercel:
   - Framework Preset: Next.js
   - Root Directory: (blank) unless your code is in a subfolder
   - Deploy

If this builds, slowly add back your project files (pages, APIs, lib) while keeping the structure.
