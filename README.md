# The Dev Kids Play School — Professional Website + Admin Panel

A self-contained working demo built for **The Dev Kids Play School**.

## Included
- Premium responsive public website
- Hero/campus image using the supplied school photo
- Programs, About, Teachers, Campus, Playground/Gallery, Future Plan
- Admission enquiry form
- Admin login + dashboard
- Admission enquiry management/status
- Student register
- Daily attendance (Present/Absent)
- Teacher profiles with photo upload, qualification, role and bio
- Gallery/playground photo upload
- School settings / future plan editor
- JSON export for admission enquiries
- Data persists in browser localStorage

## Demo login
Email: `admin@devkids.local`
Password: `Admin@123`

## Run
Option 1: Open `index.html` directly in a modern browser.

Option 2 (recommended): from this folder run:

```bash
python -m http.server 8080
```
Then open `http://localhost:8080`.

## Important
This is a **working frontend/demo management system**, not a production multi-user server. Data is stored in the browser. For production, connect the same UI to a secure backend/database (MySQL/PostgreSQL/Supabase/Firebase), real authentication, cloud file storage, backups, WhatsApp/email notifications and role-based permissions.
