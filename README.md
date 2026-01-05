# Jassim Abdul Gafoor - Personal Website

This repository hosts the personal website of Jassim Abdul Gafoor, designed as a professional landing page for networking and career opportunities, with a secondary purpose of hosting blog articles.

## Overview

The website focuses on professional areas such as digitizing and automating industrial work, AI-powered workflows, and smart contracts/blockchain technology. It is primarily targeted at recruiters and industry peers.

## Key Sections

The website includes the following main sections:
*   **Home:** Introduction and highlights.
*   **About Me:** Detailed background, experience, and interests.
*   **Case Studies:** Showcase projects with problem, solution, technologies, and outcomes.
*   **Blog:** For articles and insights, sourced from Markdown files in a separate repository.
*   **Contact:** Information for connecting with recruiters and peers.

The design is minimalist, utilizing a black and white color scheme with HTML and CSS only, ensuring responsiveness for mobile devices.

## Recent changes (local edits)

- **Navigation alignment:** Fixed CSS to use proper `align-self: center` for centering homepage navigation links (replaced invalid `align-self: middle`). See [styles.css](styles.css).
- **Curator.io feed relocation:** Moved Curator.io embed and JavaScript from contact page to blog page for better content organization. See [blog.html](blog.html).
- **Instagram link added:** Added Instagram to contact page social links. See [contact.html](contact.html).
- **Contact embed:** Replaced the Instagram link with a Curator.io feed embed and added the widget script. See [blog.html](blog.html).
- **Email UX:** Made the contact copy more action-oriented and added a clickable "[Copy]" control next to the email for easy saving/copying. See [contact.html](contact.html).
- **Social links:** Replaced SVG icon buttons with bracketed text links (e.g. [github.com/jassimga4]) and updated styling for inline display. See [contact.html](contact.html) and [styles.css](styles.css).
- **Heading alignment:** Left-aligned `h2` headings site-wide. See [styles.css](styles.css).
- **Navigation layout & sizing:** Standardized nav oval widths, reduced spacing, increased oval width so labels are not truncated, and added responsive layouts:
	- Homepage: always shows nav in a 2x2 grid (`body.home`).
	- Site pages: single-line nav on desktop; mobile uses a 2-1-2 cross grid (`body.site-page`).
	See [styles.css](styles.css) and the pages updated with `class="home"` or `class="site-page"` on the `body` element.

If you'd like these notes formatted differently or expanded into a full changelog with timestamps, I can update this section accordingly.
