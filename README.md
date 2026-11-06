# Stefano Leonardi — Academic Website (Hugo Blox / Academic Theme)

This repository contains the Hugo source code for Professor Stefano Leonardi's personal academic website, designed for easy deployment to **GitHub Pages**.

## Directory Structure

```
├── hugo.yaml                          # Main Hugo & Academic theme configuration
├── .github/workflows/deploy.yml       # Automatic GitHub Actions deployment to GitHub Pages
├── content/
│   ├── authors/admin/_index.md        # Biography, education, research interests, social links
│   ├── publication/                   # Publication entries (BibTeX / metadata / abstracts)
│   │   ├── contract-design-soda26/
│   │   ├── two-sided-markets-sicomp26/
│   │   ├── fair-division-tcs26/
│   │   └── submodular-knapsack-tcs26/
│   ├── project/                       # Research projects (e.g. ERC Grant AMDROMA)
│   │   └── amdroma/
│   └── teaching/                      # Courses taught at Sapienza DIAG
│       ├── algorithm-design/
│       └── economics-computation/
└── static/                            # Static assets (PDFs, images, CV)
```

## Running Locally

1. Install Hugo (Extended Edition recommended):
   ```bash
   brew install hugo
   ```
2. Start the local development server:
   ```bash
   hugo server -D
   ```
3. Open `http://localhost:1313` in your browser.

## Deploying to GitHub Pages

1. Push this repository to GitHub (e.g., `github.com/your-username/your-username.github.io`).
2. In your repository on GitHub, go to **Settings > Pages**.
3. Under **Build and deployment > Source**, select **GitHub Actions**.
4. Every commit to `main` will automatically build and publish your website.
