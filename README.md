# IGA DRIVER — website starter

A responsive Next.js starter for the IGA DRIVER Rwanda road-learning platform.

## Included
- Home page and responsive visual identity
- Learning-centre topic outline
- Pricing: 200 RWF single exam, 500 RWF weekly, 1,500 RWF monthly
- Registration and login interface previews
- Student dashboard preview
- Timed sample quiz interface
- Payment-submission interface preview
- Administrator dashboard preview
- Default passing score documented as 12/20

## Run locally
1. Install Node.js 20.9 or later.
2. Extract this project.
3. Open a terminal in this folder.
4. Run `npm install`.
5. Run `npm run dev`.
6. Open http://localhost:3000.

## Important production work still required
This is a working front-end starter, not a production-ready examination/payment service. The forms currently demonstrate the user experience and do not create real accounts, store exam attempts, accept payments or grant entitlements.

Before public launch, implement and test:
1. PostgreSQL database and migrations.
2. Secure phone/email registration, verification, password hashing, sessions and account recovery.
3. Server-side exam generation (20 random questions), 20-minute authoritative timer, grading, history and anti-cheating controls.
4. At least 400 reviewed questions, bilingual Kinyarwanda/English content and official-source validation.
5. Two free exams per rolling 24 hours; 200 RWF single credit that does not expire until used; 500 RWF weekly; 1,500 RWF monthly.
6. One active exam per user; default pass score 12/20, editable by an authorized administrator.
7. Manual MTN payment review initially. A screenshot or OCR result must never activate access automatically. Add MTN API integration only after credentials and merchant configuration are securely provided.
8. Private admin authentication, role-based permissions, audit logs, rate limiting, backups, HTTPS and privacy terms.

## Brand
IGA DRIVER — Learn. Practice. Drive.
Palette: road-sign red, safety green, road blue and deep navy.
