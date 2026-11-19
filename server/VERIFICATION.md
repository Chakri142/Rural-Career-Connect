# Verification record

Verified on a running Spring Boot server with MySQL 8.4 and Chromium. Test data was removed from the preview afterward.

- both public registration flows, role-specific profile redirect
- private draft, edit, publish
- normalized unique skills, 75% match, saving, applying and duplicate prevention
- employer ownership and independent application decisions, candidate notification
- shortlisting persists across re-login and appears in administrator reports
- PDF upload, authorized employer retrieval and invalid-file rejection
- read state and account deactivation
- closed vacancy hidden from discovery, application history retained
- responsive layout checks across roles at 390, 820 and 1366 px; no uncaught JS errors
- end-to-end verification complete

Initial visual review was performed on the homepage and all role dashboard shells before data wiring. Final checks include live database-backed routes. Testing covers the listed scenarios, not a security audit or production load test.
