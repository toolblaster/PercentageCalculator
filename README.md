ToolBlaster Percentage Calculator

A fast, privacy-focused, single-page percentage calculator designed for professionals and students. This tool provides 6 different percentage calculation modules with real-time results, local history, and a responsive, laptop-first design.

🚀 Live Demo

URL: https://percentagecalculator.toolblaster.com/

📂 Project Structure

/
├── index.html          # Main calculator tool
├── css/
│   └── site.css        # Global styles and shared design tokens
├── pages/
│   ├── about.html           # About page
│   ├── privacy.html         # Privacy Policy page
│   └── percentage-guide.html # Educational formulas guide
└── favicon/            # Directory for favicon assets


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

Ad-Ready & CLS Safe: Includes reserved ad slots that prevent layout shifts on the tool page, while gracefully collapsing on content pages.

🛠️ Setup & Usage

Since this is a static HTML/CSS/JS project, no build process or package manager (npm/yarn) is required.

Download: Download the files preserving the folder structure above.

Favicons: Ensure you place your generated favicon files into a root-level folder named favicon/.

Run: Open index.html directly in any modern browser or deploy to any static host (Netlify, Vercel, GitHub Pages, Apache/Nginx).

⚙️ Customization

Enabling Ads

The ad slots are structurally reserved to prevent Cumulative Layout Shift (CLS) on the calculator page but are hidden on content pages via the no-ads body class.

To enable ads on the main calculator (index.html):

Open index.html.

Locate the <div class="ad-slot ..."></div> containers.

Insert your ad network code (e.g., Google AdSense) inside these containers.

In css/site.css, locate the .ad-slot rule and change display: none to display: flex (or block) to make them visible.

Note: Content pages (Guide, About, Privacy) have a <body class="no-ads"> tag which forces these slots to collapse via CSS, keeping those pages clean.

Updating Branding

Colors: Modify the CSS variables in the :root block in css/site.css (e.g., --primary, --text-main).

Text: Update the Footer copyright year and text in index.html and pages in the pages/ directory.

📜 License

© 2026 ToolBlaster. All rights reserved.
