MAC FITNESS — CLIENT PRESENTATION PROTOTYPE (NO NODE)
link : https://lomeshsahu.github.io/MacFit/
OPEN:
Double-click index.html. No Node.js, npm, React or build process is required.

INCLUDED:
- Premium responsive landing page
- Gallery + animated gym visual
- Membership plans
- Member profile + subscription status
- Admin login + dashboard
- Member search/add/delete demo controls
- Support/contact form
- LocalStorage persistence
- Security-focused production notes

DEMO ADMIN:
Username: admin
Password: macfitness

SECURITY IMPORTANT:
This is a client/demo prototype. The admin login is intentionally a visual/demo flow and is NOT secure for production because all frontend JavaScript can be inspected by a visitor.

PRODUCTION SECURITY PLAN:
1. Supabase Auth for real user/admin authentication.
2. Separate admin role/claims.
3. PostgreSQL Row Level Security (RLS) policies for every member/subscription table.
4. Frontend uses only the public Supabase anon/publishable key.
5. Never put service-role keys, database passwords, payment secrets, or private API keys in this website.
6. Server/database-side validation for all writes.
7. Storage policies for profile/gallery uploads.
8. Audit fields/logs for admin changes.
9. HTTPS on deployment.
10. Rate limiting / CAPTCHA on public support forms.
11. Payment provider webhooks verified server-side.
12. Backups and least-privilege access.

The remote gallery photos use Unsplash URLs. Internet is needed for those images.
