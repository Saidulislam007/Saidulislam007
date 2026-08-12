# Install the Bento Engineer GitHub Profile

1. On GitHub, create a **public repository** named exactly `Saidulislam007`.
2. Keep `README.md` in the repository root.
3. Keep the entire `assets` folder beside `README.md`.
4. Commit and push all files together.

```powershell
git add README.md INSTALL.md assets
git commit -m "feat: add Bento Engineer GitHub profile README"
git push origin main
```

## Important GitHub limitation

GitHub removes normal custom CSS and does not run Tailwind CSS, Framer Motion,
Lucide React or JavaScript inside a profile README. This package uses embedded
CSS animations inside custom SVG files, which keeps the Bento Engineer look
while remaining compatible with GitHub.

## Profile image

The profile photo is embedded into `assets/hero-banner.png`, so it appears
inside the banner and renders consistently on GitHub.

The compact professional introduction is rendered from `assets/about-me.png`.
