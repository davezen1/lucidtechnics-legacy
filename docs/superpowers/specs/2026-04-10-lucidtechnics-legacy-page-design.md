# Design Spec: Lucid Technics Legacy Page

## 1. Overview
A single-page, static HTML website serving as a legacy placeholder for the former consulting company, Lucid Technics. The goal is to provide a simple, elegant, and professional statement about the company's history.

## 2. Architecture
*   **Technology:** Plain HTML5 and CSS3. No build tools or JavaScript required.
*   **Structure:** A single `index.html` file with embedded CSS for maximum portability.

## 3. Visual Design
*   **Theme:** Minimalist Center (Black text on White background).
*   **Typography:** Clean sans-serif system fonts (e.g., `-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif`).
*   **Layout:**
    *   Flexbox-based centering (`justify-content: center`, `align-items: center`).
    *   Full viewport height (`min-height: 100vh`).
    *   Heading: `h1` element, uppercase, with generous letter-spacing (`~4px`) and light font-weight (`~300`).
    *   Body: Paragraph with a comfortable `max-width` (e.g., `600px`), `line-height` of `~1.8`, and slightly muted color (e.g., `#333`) to ensure high contrast without being harsh.

## 4. Content
*   **Heading:** LUCID TECHNICS
*   **Paragraph:** "Lucid Technics was a consulting company founded by David Hodge that served startups, non-profits, Fortune 500 companies, and large government agencies."

## 5. Accessibility
*   Semantic HTML tags (`<main>`, `<h1>`, `<p>`).
*   Valid contrast ratios for text.
*   Responsive design that works on all viewport sizes without horizontal scrolling.