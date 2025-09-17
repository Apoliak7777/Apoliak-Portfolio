# Apoliak-Portfolio

A PHP-based personal developer portfolio designed to showcase projects, skills, experience, and contact information in a structured and extensible way. This repository focuses on a classic server-rendered approach (likely mixing PHP templates with HTML/CSS) rather than a heavy JavaScript framework, keeping it lightweight and easy to deploy on standard hosting.

## Goals

- Present professional and personal projects
- Provide an "About Me" narrative with skills and technologies
- Offer a contact channel (form or direct links)
- Maintain a modular structure for adding sections (timeline, blog, services, etc.)
- Use custom CSS for branding and layout consistency

## Potential / Common Features

- Project listing with descriptions, tags, and links (e.g., GitHub or live demos)
- Dynamic includes for header, footer, and navigation
- A configurable skill matrix (frontend, backend, tools)
- Contact form (could be processed by PHP mail or third-party API)
- Multi-page structure: Home, Projects, About, Contact
- SEO meta tags and social preview data

(You can refine this section once actual file names and features are confirmed.)

## Tech Stack

- Backend / Templating: PHP
- Styling: CSS (primary language detected)
- Optional Enhancements:
  - JavaScript for animations or interactive filtering
  - JSON/PHP arrays for structured project data
  - Simple admin editing (future)

## Suggested File / Directory Structure (Adjust to Actual)

```
/assets
  /css
  /img
  /js
/includes
  header.php
  footer.php
  nav.php
/pages
  projects.php
  contact.php
index.php
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Apoliak7777/Apoliak-Portfolio.git
   cd Apoliak-Portfolio
   ```
2. Serve with PHP’s built-in server (development):
   ```bash
   php -S localhost:8000
   ```
3. Open http://localhost:8000 in your browser.

## Deployment

You can deploy to:
- Shared hosting (upload files via FTP)
- VPS with Apache or Nginx + PHP-FPM
- Docker (create a simple `Dockerfile` with `php:apache` base)
- GitHub Actions workflow for automatic deploy (future enhancement)

## Recommended Next Steps

- Add a `/data/projects.php` or JSON file to centralize project definitions
- Implement a reusable component system via `include` or `require`
- Add form validation + spam protection (honeypot or reCAPTCHA)
- Introduce dark/light theme toggle
- Optimize images and add favicons
- Add Open Graph + Twitter Card meta tags

## Contributing

1. Fork the repository
2. Create a feature branch:
   ```bash
   git checkout -b feature/project-database
   ```
3. Commit changes:
   ```bash
   git commit -m "Add structured project data system"
   ```
4. Open a pull request

## License

Licensed under the GNU General Public License v3.0 (GPL-3.0).  
See the `LICENSE` file for full details.

## Contact

For collaboration or questions:  
[Apoliak7777 on GitHub](https://github.com/Apoliak7777)

---


<img width="950" height="477" alt="image" src="https://github.com/user-attachments/assets/7eb52bf7-74ec-41a6-b09b-eb0f2d953072" />
<img width="940" height="475" alt="image" src="https://github.com/user-attachments/assets/e0ed8a03-15ff-44c9-98a4-f92f0374bde3" />
<img width="945" height="477" alt="image" src="https://github.com/user-attachments/assets/07ca4a70-68b7-49d4-b2a8-d9573bcdd996" />
<img width="951" height="474" alt="image" src="https://github.com/user-attachments/assets/e0fb0cbe-561f-4467-ba4b-e1e55d48aef7" />
