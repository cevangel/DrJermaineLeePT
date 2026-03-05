# Value-Add Ideas for Jermaine Lee Physical Therapy PLLC

Quick wins and future enhancements to give the client more value from the website.

---

## 1. New Patient Intake via Google Form (recommended)

**Why:** Speeds up intake, collects info before the first visit, and reduces front-desk work. The current "Request Appointment" form on the site does not submit anywhere (no backend).

**How:**
- Create a **Google Form** with fields the practice needs: name, DOB, phone, email, insurance, chief complaint, referral (if any), preferred location/time, and any HIPAA-friendly intake questions they already use on paper.
- In Google Forms: **Responses** → **Link to Sheets** so they get a spreadsheet of submissions (or email notifications).
- On the site: add a clear **"New Patient Intake"** or **"Complete Intake Before Your Visit"** link/button that goes to the form (or embed the form in an iframe on a dedicated page).
- Optional: keep the existing "Request Appointment" section for quick name/email/date requests, and use the Google Form for **full intake** so staff have everything before the first visit.

**Suggested form fields (client can customize):**
- Full name, Date of birth, Phone, Email
- Preferred appointment time (or "earliest available")
- Insurance (name + ID if needed)
- Primary reason for visit / chief complaint
- Referring provider (if any)
- How did you hear about us?
- Any questions or notes

---

## 2. Other high-value additions

| Idea | Benefit | Effort |
|------|---------|--------|
| **Online scheduling link** | Let patients book directly (e.g. Acuity, Calendly, or their EMR’s patient portal). Add a "Book Online" button next to "Request Appointment." | Low (link only) |
| **Replace placeholder content** | Real testimonials, real clinician names/bios, real address/phone/email site-wide (currently placeholders in footer/header). | Medium (content from client) |
| **FAQ page** | "Do you take my insurance?", "What should I bring?", "First visit?" — cuts calls and builds trust. | Low–medium |
| **Service-area / boroughs** | Short section or page: "We serve the five boroughs" + any in-home or specific neighborhoods. Good for local SEO. | Low |
| **Email signup** | Newsletter or "PT tips" signup (e.g. Mailchimp) — capture leads and stay in touch. Footer already has a signup box; connect it to a real list. | Low (once provider chosen) |
| **Simple blog or resources** | 1–2 articles (e.g. "What to expect at your first PT visit," "Stretching tips") to help SEO and position Dr. Lee as expert. | Medium (content from client) |

---

## 3. Technical note on current forms

- **Home page:** "Request Appointment" form has no `action` — submissions go nowhere.
- **Contact page:** Contact form uses `action="#"` — also no backend.

**Options:**  
- **Quick:** Use Google Form for intake (and optionally for contact) and link/embed it.  
- **Later:** Add a form backend (e.g. Formspree, Netlify Forms, or their host’s form handler) so the existing forms submit to the client’s email or CRM.

---

Use this doc to agree with the client on which items to do now (e.g. Google Form intake + real contact info) vs later (blog, scheduling integration).

---

## 4. Images and stock photos

**Using stock photos:** Yes, it’s fine to use stock photos for generic scenes (e.g. someone stretching, a person in PT, a calm recovery setting) as long as they’re not misleading. Avoid using stock for “our team” or “our facility” — those should be real photos or removed.

**Best approach:** Use the 1–2 real photos of Dr. Lee treating patients where they matter most (e.g. About page, Our Clinicians). Use stock for hero images, general “physical therapy” or “recovery” imagery, or background shots. If a section has no real image and no suitable stock pick, remove the image or use a simple graphic/icon so the site doesn’t look unfinished.
