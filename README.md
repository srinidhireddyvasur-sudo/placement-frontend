# Frontend

Plain HTML / CSS / JavaScript (no build step).

- `index.html` - login and student registration
- `student.html` - student dashboard
- `admin.html` - admin dashboard
- `css/style.css`, `js/app.js` - shared styles and helpers

Pages call the backend with relative URLs (`/api/...`, `/login`, `/logout`). The backend build copies this folder into its static resources, so edit files here and redeploy.
