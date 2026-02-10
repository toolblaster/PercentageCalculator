ToolBlaster Percentage Calculator

A fast, privacy-focused, single-page percentage calculator designed for professionals and students. This tool provides 6 different percentage calculation modules with real-time results, local history, and a responsive, laptop-first design.

🚀 Live Demo

URL: https://percentagecalculator.toolblaster.com/

📂 Project Structure

/
├── index.html          # Main calculator tool (formerly percentage-calculator.html)
├── pages/
│   ├── about.html      # About page describing the tool's philosophy
│   └── privacy.html    # Privacy Policy page
└── favicon/            # Directory for favicon assets (refer to list below)
    ├── web-app-manifest-192x192.png
    ├── site.webmanifest
    ├── favicon-96x96.png
    ├── favicon-48x48.png
    ├── favicon-32x32.png
    ├── favicon-16x16.png
    ├── apple-touch-icon.png
    └── android-chrome-*.png


✨ Key Features

6 Calculation Modules:

Find Percentage of a Number

Find What Percentage X is of Y

Find Total Given a Percentage

Percentage Increase

Percentage Decrease

Percentage Difference

Real-time Calculation: No "Calculate" button; results update instantly on input.

Local History: Saves the last 3-5 valid calculations per card using LocalStorage.

Input Memory: Remembers input values on page reload so users don't lose work.

Zero-Knowledge Privacy: All logic runs client-side. No data is sent to any server.

Responsive Design: Optimized for laptop screens (3-column grid) while fully mobile-responsive.

SEO Optimized: Includes valid JSON-LD Schema (WebPage, FAQPage) and Open Graph tags.

Ad-Ready: Includes CLS-safe, locked ad placeholders (.ad-slot) hidden by default.

🛠️ Setup & Usage

Since this is a static HTML/CSS/JS project, no build process or package manager (npm/yarn) is required.

Download: Download the files preserving the folder structure above.

Favicons: Ensure you place your generated favicon files into a root-level folder named favicon/.

Run: Open index.html directly in any modern browser or deploy to any static host (Netlify, Vercel, GitHub Pages, Apache/Nginx).

⚙️ Customization

Enabling Ads

The ad slots are currently hidden (display: none) but structurally reserved to prevent Cumulative Layout Shift (CLS).
To enable them:

Open index.html.

Search for .ad-slot in the <style> block.

Change display: none; to display: flex;.

Uncomment height: 100px; and margin: 0.5rem auto;.

Insert your ad code inside the HTML <div class="ad-slot ..."></div> containers.

Updating Branding

Colors: Modify the CSS variables in the :root block (e.g., --primary, --text-main) in all HTML files.

Text: Update the Footer copyright year and text in index.html, pages/about.html, and pages/privacy.html.

📜 License

© 2026 ToolBlaster. All rights reserved.
