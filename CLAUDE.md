# Business Analyst Portfolio — Project Instructions

## 1. Project Overview

Build a premium personal portfolio website for a Business Analyst / Project Manager.

The website should present my professional profile, experience, projects, skills, tools, education, certifications, and contact information.

### Target Audience
- Recruiters and HR professionals
- Hiring managers
- Product and project management teams
- Potential clients

### Professional Capabilities to Communicate
- Business analysis and requirement gathering
- Stakeholder management
- Business process analysis
- Functional documentation and specifications
- Agile/Scrum project delivery
- QA testing, UAT, and acceptance criteria
- Web and mobile application projects
- Product and project coordination
- Third-party API and payment gateway integrations

Do not invent employment history, project outcomes, certifications, personal details, or performance metrics. Use clearly identifiable placeholders whenever information is missing.

---

## 2. Design System

The website should have an elegant, minimal, premium, recruiter-friendly appearance.

### Visual Direction
- Dominant jet-black background
- Warm bronze and brown accent colors
- Strong typography and clear visual hierarchy
- Generous spacing and balanced composition
- Subtle borders and restrained hover effects
- Clean, polished, professional presentation
- Responsive design for desktop, tablet, and mobile

### Avoid
- Generic portfolio templates
- Excessive gradients
- Unnecessary animations
- Cluttered layouts
- Excessive decorative elements
- Inconsistent typography or spacing

### Design Reference
When I provide a reference image:
- Treat it as the primary visual reference.
- Match its layout, color palette, typography, spacing, and visual hierarchy as closely as reasonably possible.
- Do not claim an exact replica unless the implementation genuinely matches the reference.
- If the reference image is not accessible, ask me to provide it before attempting to reproduce it.
- Do not invent image paths or assume an image exists.

---

## 3. Website Structure

The complete portfolio should include:

1. Navigation
2. Hero / Introduction
3. About Me
4. Professional Experience
5. Featured Projects
6. Skills
7. Tools & Technologies
8. Education
9. Certifications
10. Contact
11. Footer

### Navigation
- Name or logo on the left
- About, Experience, Projects, Skills, and Contact links on the right
- Responsive mobile navigation
- Smooth navigation to relevant sections

### Hero Section
- Name and professional title
- Title: Business Analyst | Project Manager
- Concise professional introduction
- CTA buttons: View Projects and Contact Me
- Profile illustration or portrait area on the right side
- Inspect the public folder for an existing suitable image before using one.
- If no suitable image exists, create a polished placeholder that can be replaced later.

### About Section
Provide a concise professional summary focused on business analysis, requirements, stakeholder coordination, and product delivery.

### Professional Experience
Present employment details in a clear and readable format. Use placeholders for missing dates, company details, or responsibilities.

### Featured Projects
Use clean, consistent project cards. Each card should support:
- Project name
- Domain or category
- Short project description
- Key responsibilities or contributions
- Relevant technologies or integrations
- Link to the project website or app, when available

Do not invent project links, achievements, or measurable outcomes.

### Skills and Tools
Present skills and tools in clear, organized groups. Avoid excessive badges or decorative elements.

### Contact
Include LinkedIn, email, and phone placeholders where actual details are unavailable.

### Footer
Include a minimal footer with relevant navigation or contact links.

---

## 4. Technology Stack

Use the existing project configuration and installed dependencies.

### Core Stack
- Next.js App Router
- React
- TypeScript
- Tailwind CSS
- ESLint

### Preferred Supporting Tools
- Motion for restrained animations, only when necessary
- Lucide React for consistent icons
- GitHub for version control
- Vercel for deployment

### Technical Rules
- Inspect installed versions and configuration before making changes.
- Prefer existing dependencies and capabilities.
- Do not install additional packages without a clear benefit.
- Do not introduce a backend or database unless explicitly requested.
- Use TypeScript and follow existing ESLint conventions.
- Use semantic and accessible HTML.
- Keep layouts responsive and mobile-friendly.

---

## 5. Component and Code Structure

Use a component-based architecture.

Keep major homepage sections in separate, reusable components where appropriate.

Suggested structure:

src/
  app/
    page.tsx
    globals.css
  components/
    Navbar.tsx
    Hero.tsx
    About.tsx
    Experience.tsx
    Projects.tsx
    Skills.tsx
    Contact.tsx
    Footer.tsx

This is a suggested structure, not a requirement to create every file immediately. Inspect the existing project first and adapt the structure when necessary.

### Code Quality
- Keep components readable and maintainable.
- Avoid unnecessarily large components.
- Keep repeated content organized in simple data arrays where appropriate.
- Avoid unnecessary abstractions.
- Do not create redundant files.
- Do not overwrite or delete existing files without explaining why.

---

## 6. Development Workflow

Work in small, reviewable stages.

Before implementation:
1. Inspect the existing project structure.
2. Inspect the relevant dependencies and configuration.
3. Identify the files that need to change.
4. Explain the proposed implementation plan.
5. Wait for my approval before making code changes.

After implementation:
1. Summarize the changes made.
2. List the files created or modified.
3. Report any checks performed, such as compilation or linting.
4. Explain what I should verify in the browser.
5. Identify any remaining placeholders or issues.

Do not claim that the project compiles or passes checks unless those checks were actually performed.

---

## 7. Collaboration and Learning Style

I am learning web development while building this portfolio.

For each stage:
1. Explain the goal in simple terms.
2. Explain the proposed approach.
3. Identify the files to be changed.
4. Wait for my approval before coding.
5. Implement the approved task.
6. Explain how I can verify the result locally.

Keep explanations concise, practical, and step-by-step.

Do not rush through multiple stages without giving me an opportunity to review the result.

If a requirement is unclear, ask me before making a major design or architecture decision.

---

## 8. Current Project Information

- Project: Personal Business Analyst / Project Manager Portfolio
- Framework: Next.js
- Local development URL: http://localhost:3000
- GitHub repository: https://github.com/akmalkk786/ma-portfolio
- Project instructions: This CLAUDE.md file

The project has already been created and connected to GitHub.

Do not initialize another repository or create a duplicate Next.js project.

---

## 9. Current Development Stage

The current stage is the homepage and initial design system.

The homepage should include:
- Navigation
- Hero section
- About section
- Featured projects
- Skills and tools
- Contact section
- Footer

Professional experience, education, and certifications are part of the complete website structure and can be added or refined in later stages.

### Next Task
Inspect the existing project structure and dependencies.

Then propose:
- The homepage component structure
- The files to create or modify
- The design implementation approach
- Any missing assets or information

Wait for my approval before making code changes.

Do not begin a new implementation automatically just because this file has been updated.