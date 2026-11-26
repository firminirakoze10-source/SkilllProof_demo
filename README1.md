# SkillProof

**Making skills visible. Opening pathways to opportunity.**

SkillProof is a web-based prototype designed to help refugees and displaced professionals present their skills, work experience, education, and credentials in a structured way. It aims to make it easier for candidates to demonstrate what they can do, even when they have lost access to some original documents.

## The Problem

Refugees and displaced professionals may have valuable skills, education, and work experience but face difficulties proving their qualifications. Documents can be lost during displacement, and employers may struggle to assess experience when conventional records are unavailable.

SkillProof explores a digital approach to organising candidate profiles, submitted credentials, and assessed skills so that information can be reviewed and shared with consent.

## Project Objectives

- Give candidates a place to describe their education, experience, and skills.
- Allow candidates to submit details of credentials and supporting evidence for review.
- Provide reviewers with a dashboard for assessing submitted credentials and skills.
- Help employers discover talent through skills and qualifications.
- Give candidates control over whether their profiles are shared.
- Provide a competency report that summarises verified credentials and assessed skills.

## Main Features

### Candidate profiles
Candidates can create a profile containing a headline, country, summary, education, and work experience.

### Credential submissions
Candidates can submit details for different types of credentials, including:

- Degrees and diplomas
- Professional certificates
- Trade certificates
- Licences
- Employer references
- Other supporting credentials

Credential submissions can be tracked through the following statuses:

- `pending`
- `in_review`
- `verified`
- `unverifiable`

### Skills and experience
Candidates can list skills, select a proficiency level, indicate years of experience, and provide evidence links. The available proficiency levels are Beginner, Basic, Competent, Advanced, and Expert. Reviewers can assess submitted skills.

### Reviewer dashboard
Reviewers can inspect credential submissions, update their status, add notes, and assess candidates' skills.

### Employer search
The employer view allows employers to search for skills and qualifications and view talent that candidates have chosen to share.

### Competency reports
The platform can generate a competency report showing verified credentials and assessed skills. Reports include a report code and can be printed or saved as a PDF through the browser.

### Privacy and candidate control
The prototype includes consent-based sharing controls. Candidates can change their sharing preference, download their data in JSON format, and delete their account from the prototype.

### Multiple languages
The interface includes language options for:

- English
- French
- Arabic
- Kiswahili

## Technology Stack

The current prototype uses:

- **HTML5** for page structure
- **CSS3** for styling and responsive presentation
- **JavaScript** for application behaviour and interactions
- **Browser LocalStorage** for demo data persistence
- **Google Fonts (Manrope)** for typography

The current implementation is a self-contained HTML file with its CSS and JavaScript embedded in that file.

## User Roles

| Role | Main capabilities |
|---|---|
| Candidate | Create a profile, list skills and experience, submit credentials, manage sharing, and view competency reports |
| Reviewer | Review credential submissions, update statuses, add notes, and assess skills |
| Employer | Search for skills and qualifications and view profiles shared by candidates |

## Demo Access

The prototype includes demonstration accounts for testing the different user roles.

| Role | Demo email |
|---|---|
| Candidate | `amina@demo.org` |
| Candidate | `joseph@demo.org` |
| Reviewer | `reviewer@demo.org` |
| Employer | `employer@demo.org` |

**Demo password:** `demo1234`  
**Reviewer code:** `assess-2026`

These are demonstration credentials included for evaluation of the prototype. Do not use them as real account credentials.

## Running the Project Locally

1. Download or clone the project repository.
2. Locate the main HTML file.
3. Open the HTML file in a modern web browser.

No build process or package installation is required for the current standalone prototype.

## Project Structure

The current application is implemented as a single HTML file. A simple repository layout may look like this:

```text
SkillProof/
├── index.html
├── README.md
└── presentation/
    ├── pitch-deck.pptx
    └── pitch-deck.pdf
```

The `presentation` folder is optional and should be included only if the pitch deck files are part of the submitted project. The HTML file contains the page markup, styling, and JavaScript.

## Current Limitations

SkillProof is currently a demonstration prototype, not a production-ready service.

- Application data is stored in the browser using LocalStorage; it is not stored in a central database.
- The demonstration login and reviewer access mechanisms are not suitable for production use.
- Credential review is simulated within the prototype; there is no integration with universities, employers, licensing bodies, or other credential-issuing institutions.
- The credential submission interface records file names, but does not provide secure server-side file storage or document processing.
- The demo accounts and sample records are intended for evaluation only.
- The prototype does not yet include a production backend, server-side authorisation, or a complete security and privacy architecture.

Do not enter sensitive personal information or real identity documents into this demonstration version.

## Future Improvements

Potential next development stages include:

- Build a secure backend and database.
- Implement production-grade authentication, role-based access control, and account recovery.
- Add secure document upload, storage, and review workflows.
- Establish verification partnerships with education providers, employers, and professional bodies.
- Add audit logs so credential decisions and reviewer actions can be traced.
- Strengthen consent management, data protection, and privacy controls.
- Conduct usability and accessibility testing with refugee and displaced communities.
- Deploy a production version with monitoring, backups, and operational support.

## Social Impact

SkillProof is intended to help make skills and experience more visible when displacement interrupts access to traditional records. By organising candidate information and providing a review workflow, the concept aims to support fairer recognition of talent and improve pathways towards education, employment, and professional opportunities.

The prototype demonstrates the concept and its core user journeys. Its verification and data-handling capabilities would need further technical development and institutional collaboration before real-world use.

## Deployment

The static prototype can be hosted on a service such as Netlify once the project files are pushed to a Git repository. For a basic deployment, configure the site to publish the directory containing the main HTML file. A deployed demonstration should be clearly labelled as a prototype and should not collect real sensitive documents or personal data.

## Author

**Irakoze Firmin**

---

*SkillProof — Making skills visible. Opening pathways to opportunity.*
