# TechJam-experience-Repo

🌟 Inspiration
We initially toyed with the idea of a playful, kid-friendly privacy tool themed around the Cookie Monster — something whimsical and engaging for younger audiences. But as we scoped out the broader impact and use cases, we pivoted toward a more universally applicable solution: AnonymousDoc AI. This direction allowed us to focus on real-world privacy challenges, especially in education, healthcare, and legal contexts, where sensitive documents need to be redacted quickly and responsibly. The shift wasn’t just thematic — it was strategic. We wanted something that could scale, teach, and empower.

🧠 What It Does
AnonymousDoc AI is a privacy-first document redaction tool that:

Accepts PDF uploads via a clean, intuitive interface

Analyzes text using NLP and regex to detect sensitive entities (names, emails, locations, etc.)

Scores the document’s sensitivity level

Previews both the original and redacted versions

Generates downloadable redacted PDFs with visual overlays

It’s designed to be modular, teachable, and hackathon-ready — perfect for rapid prototyping, contributor onboarding, or CTF-style challenges.

🛠️ How We Built It
Frontend: Vanilla HTML/CSS/JS scaffolded into modular components (UploadZone, ScoreBadge, ProgressBar, etc.), later migrated to React + TypeScript for maintainability

Backend: FastAPI with spaCy for entity detection, PyMuPDF for PDF parsing and redaction, and CORS middleware for seamless frontend integration

Workflow: File upload → NLP analysis → sensitivity scoring → redaction overlay → export

We emphasized reusable logic, clean state management, and pedagogical clarity throughout.

🧩 Challenges We Ran Into
Getting PyMuPDF to reliably extract and redact text across diverse PDF formats

Handling image-based PDFs with no extractable text

Managing CORS and multipart form data in a local dev environment

Designing a scoring rubric that balances direct and indirect identifiers

Debugging async file handling between frontend and backend

Each challenge became a learning artifact — documented, modularized, and turned into flashcards or checklists for future contributors.

🏆 Accomplishments That We're Proud Of
Built a fully functional privacy tool from scratch in a short time frame

Migrated from vanilla JS to React + TypeScript with reusable components

Created a backend that not only analyzes but transforms documents

Designed a scoring system that’s explainable and extensible

Documented every major bug fix and architectural decision for teaching

📚 What We Learned
How to bridge frontend-backend workflows with FormData and streaming responses

How to use spaCy and regex together for layered entity detection

How to scaffold modular components that are both functional and pedagogically useful

How to turn technical setbacks into reusable learning resources

How to design for trust, transparency, and privacy in UX

🚀 What's Next for AnonymousDoc AI
Add drag-and-drop support and mobile responsiveness

Expand entity detection with multilingual models and OCR for image-based PDFs

Build a contributor dashboard with flashcards, checklists, and onboarding flows

Integrate with secure cloud storage for document retention and audit trails

Launch a teaching version with sandboxed redaction challenges for students and CTFs

Let me know if you want this formatted for a README, Devpost, or slide deck. I can also scaffold a contributor guide or flashcard set based on this write-up.

could you write it in a copy pasteable format
Of course! Here's a clean, copy-pasteable version of your AnonymousDoc AI write-up, formatted for Devpost, README, or any hackathon submission:

🌟 Inspiration
We initially considered building a playful, kid-friendly privacy tool themed around the Cookie Monster. It was fun and engaging, but ultimately we pivoted to something more universally applicable: AnonymousDoc AI. This direction allowed us to tackle real-world privacy challenges in education, healthcare, and legal contexts, where sensitive documents need to be redacted quickly and responsibly. The shift wasn’t just thematic — it was strategic. We wanted something that could scale, teach, and empower.

🧠 What It Does
AnonymousDoc AI is a privacy-first document redaction tool that:

Accepts PDF uploads via a clean, intuitive interface

Analyzes text using NLP and regex to detect sensitive entities (names, emails, locations, etc.)

Scores the document’s sensitivity level

Previews both the original and redacted versions

Generates downloadable redacted PDFs with visual overlays

It’s designed to be modular, teachable, and hackathon-ready — perfect for rapid prototyping, contributor onboarding, or CTF-style challenges.

🛠️ How We Built It
Frontend: Started with vanilla HTML/CSS/JS, then migrated to React + TypeScript using Vite for modularity and maintainability

Backend: FastAPI with spaCy for entity detection, PyMuPDF for PDF parsing and redaction, and CORS middleware for seamless integration

Workflow: File upload → NLP analysis → sensitivity scoring → redaction overlay → export

We emphasized reusable logic, clean state management, and pedagogical clarity throughout.

🧩 Challenges We Ran Into
Getting PyMuPDF to reliably extract and redact text across diverse PDF formats

Handling image-based PDFs with no extractable text

Managing CORS and multipart form data in a local dev environment

Designing a scoring rubric that balances direct and indirect identifiers

Debugging async file handling between frontend and backend

Each challenge became a learning artifact — documented, modularized, and turned into flashcards or checklists for future contributors.

🏆 Accomplishments That We're Proud Of
Built a fully functional privacy tool from scratch in a short time frame

Migrated from vanilla JS to React + TypeScript with reusable components

Created a backend that not only analyzes but transforms documents

Designed a scoring system that’s explainable and extensible

Documented every major bug fix and architectural decision for teaching

📚 What We Learned
How to bridge frontend-backend workflows with FormData and streaming responses

How to use spaCy and regex together for layered entity detection

How to scaffold modular components that are both functional and pedagogically useful

How to turn technical setbacks into reusable learning resources

How to design for trust, transparency, and privacy in UX

🚀 What's Next for AnonymousDoc AI

Expand entity detection with multilingual models and OCR for image-based PDFs

Build a contributor dashboard with flashcards, checklists, and onboarding flows

Integrate with secure cloud storage for document retention and audit trails

Launch a teaching version with sandboxed redaction challenges for students and CTFs



“I led the frontend development and integration for AnonymousDoc AI, a privacy-first document redaction tool designed for hackathon deployment and teaching use. I started by scaffolding a vanilla JS prototype, then migrated to React + TypeScript to ensure modularity and long-term maintainability. I built reusable components like UploadZone for drag-and-drop file handling, ProgressBar for real-time feedback, and PreviewPane for redaction visualization.”

“On the integration side, I connected the frontend to a FastAPI backend using FormData and streaming responses, which allowed for efficient PDF parsing and redaction previews. I troubleshot CORS issues, async workflows, and multipart file handling — and documented each fix as reusable checklists and flashcards for future learners.”
