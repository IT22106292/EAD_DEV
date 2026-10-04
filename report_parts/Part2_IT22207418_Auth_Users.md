# Part 2 — IT22207418 Wimalarathna A.R.S.A — Auth, Users & Web Management (25%)

**Weight:** 25% of full report (~110 of ~444 pages equivalent)
**Theme:** Identity, onboarding lifecycle, backoffice web portal

## A. Documentation Sections to Own
- [ ] Document Control + Revision History (v1.0–v3.0) + Abbreviations (JWT, OTP, NIC, FAT)
- [ ] 1. Executive Summary — Role-based access, pending-approval, email-change workflow
- [ ] 1.1 Technology Stack — Table 1 (Backend .NET 11, Auth JWT/BCrypt, Mail SMTP, React 19, Axios)
- [ ] 2.2 Use Case Diagram — Actors + Auth & User Lifecycle subsystems
- [ ] 2.4 REST API Reference — Table 4 `Auth` + Table 5 `Users`
- [ ] 3.1 MongoDB — Table 9 `UserDetails` (NIC PK, OTP, email-history rate limit)
- [ ] List of Tables/Figures entries for Tables 1, 4, 5, 9

## B. Code Paste Scope (Section 4)
**4.1 Backend:**
- [ ] `Program.cs` (DI, JWT, CORS, seeder), `MongoDbContext.cs`, `DbSeeder.cs` (users part)
- [ ] `AuthController.cs` + `AuthService.cs` (register/login/OTP), `EmailService.cs`
- [ ] `UsersController.cs` + `UserService.cs`, `AuthDtos.cs`, `UserDtos.cs`, `UserDetails.cs`, `User.cs`

**4.2 Web — Auth + Users:**
- [ ] Login, Register, OTP reset, Pending-prosumers queue, Users list/filters, Profile, Email-update review, Staff create
- [ ] Axios base + JWT interceptor + 401 auto-logout

**4.3 Android — Auth (supporting):**
- [ ] `LoginActivity.java`, `RegisterActivity.java`, `SplashActivity.java`, `OnboardingActivity.java` + layouts

## C. Other Report Parts
- [ ] 5. Git Repository + Workspace Structure + Service Base URLs (Table 16, 17)
- [ ] 5. Screenshots — Web login, register, pending queue, user management, email-update flow
- [ ] 5. Web Page Inventory (Table 18) — auth/user pages
- [ ] 6. Individual Contributions — IT22207418 detailed breakdown
- [ ] 7. Challenge 1 (NIC PK migration) + Challenge 4 (Email rate-limit & approval)
- [ ] 8. References — JWT/BCrypt/OTP/MongoDB sources (3–4 refs)

## D. Definition of Done
Auth flows runnable end-to-end (register → pending → activate → login → OTP reset), code pastes complete, screenshots match running UI.
