# MaiSpa — development website

Static, responsive first-stage homepage for MaiSpa Thai Massage & Therapy.

## Cloudflare Pages
- Production branch: main
- Framework preset: None
- Build command: leave blank
- Build output directory: /
- No custom domain is required; Cloudflare will assign a temporary *.pages.dev address.

The current site is a visual prototype. Treatment prices, contact details, location, social links and booking functionality are placeholders and must be confirmed before launch.

## Admin prototype
- Open `admin.html` to access the development admin dashboard.
- Prototype sections: dashboard, treatment editor, homepage content, gallery preview, contact details/opening hours, bookings placeholder, settings.
- The current prototype saves data in browser localStorage only. It is not authenticated, not shared between browsers/devices, and does not update the public homepage yet. Do not use it for real customer or booking data.
- Before operational use, implement secure authentication, shared database, content API, image storage, and booking backend.


## Customer CRM prototype
The admin now includes a browser-local Customer CRM prototype: phone/name lookup, customer profiles, duplicate phone matching, editing/deleting prototype records, and treatment history entries (date, service, therapist, duration, amount paid, notes). Data is stored in localStorage only. Do not use real customer information; the CRM is not secure, shared, or backed up. Operational launch requires authentication, secure server/database, access controls, retention/privacy rules, and automatic booking-to-customer matching.
