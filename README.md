# Enhanced Form – Bursary Application

## Overview
This project contains an HTML form designed for a **Bursary Application** process.  
It collects personal, educational, and financial details, along with required documents and declarations.  
The form also supports multimedia uploads for additional proof and personal introduction.

---

## Features
- **Navigation Bar** with internal links to form sections.
- **Personal Information Section**:
  - Full Name, Email, Phone Number, Date of Birth, and National ID fields.
- **Education Background Section**:
  - Current Institution, Course of Study, and Level of Study dropdown.
- **Financial Needs Section**:
  - Textarea for financial need explanation.
  - Table for family member details.
- **Requirements Section**:
  - Nested lists for personal and financial documents.
- **Supportive Multimedia Section**:
  - Upload fields for images, PDFs, audio, and video files.
- **Definition List** explaining bursary-related terms.
- **Declaration Section**:
  - Signature and date fields confirming truthfulness of the provided information.
- **Important Notice Sidebar** for applicant guidance.
- **Download Link** to a PDF application form.

---

## File Structure


---

## Form Sections and IDs
| Section Name             | HTML ID                 | Purpose |
|--------------------------|-------------------------|---------|
| Personal Information     | `#personal-info`        | Collects personal details |
| Education Background     | `#education-background` | Captures academic details |
| Financial Needs          | `#financial-needs`      | Explains need and family info |
| Requirements             | `#requirements`         | Lists required documents |
| Supportive Multimedia    | `#supportive-multimedia`| Accepts file uploads |
| Declaration              | `#declaration`          | Final confirmation |

---

## How to Use
1. **Open** `index.html` in a web browser.
2. **Navigate** through sections using the navigation menu.
3. **Fill in** all required fields (`required` attribute is enforced).
4. **Attach** necessary documents and multimedia.
5. **Submit** the completed form (submission handler not implemented in this HTML file).

---

## Notes
- The form is **front-end only**; server-side processing needs to be implemented separately.
- Some input attributes in the file have syntax errors (e.g., `input type=""text"`), which should be fixed before deployment.
- The file upload section accepts only specific file types (`image/*`, `.pdf`, `audio/*`, `video/*`).
- Navigation links use internal section IDs for smooth scrolling.

---

## License
This form can be modified and reused for educational and administrative purposes.



