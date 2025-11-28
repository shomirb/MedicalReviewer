 # MedicalReviewer
-A simple webapp to help a medical reviewer process and analyze insurance plan, patient care summary, and medical reviewer response documents. 
+
+A simple PHP/HTML/JS webapp to help a medical reviewer process and analyze insurance plan, patient care summary, and medical reviewer response documents.
+
+## Features
+- Upload insurance plans, patient care summaries, and reviewer responses (files saved to `uploads/`).
+- Paste content from two source documents for quick copy/paste workflows.
+- Manage four reusable LLM prompts stored in `data/prompts.json` with in-app editing.
+- Responsive layout suitable for AWS Lightsail hosting.
+
+## Getting started
+1. Ensure PHP 8+ is installed on the server.
+2. Clone the repository to your web root (e.g., `/var/www/html/MedicalReviewer`).
+3. Make sure the web server user can write to the `data/` and `uploads/` directories.
+4. Access `index.php` via your browser to upload documents and manage prompts.
+
+The current version focuses on collecting inputs. Future updates will connect the fields to OpenAI and Landing.ai APIs using the saved prompts.
