# GoGo Board — Privacy Policy (Source Document)
**Product:** GoGo Board Web App
**Status:** Working source document — used to draft the public-facing privacy policy
**Version:** 1.0-draft1
**Effective date:** Pending
**Last reviewed:** 2026-04-14

---

## 1. Platform Overview

- Platform name: The GoGo Board
- Primary website / app URL(s): https://www.gogoboard.org, https://code.gogoboard.org
- Description: The GoGo Board is an education-focused hardware and software platform for STEM learning, enabling students to learn programming, sensors, robotics, IoT, and basic AI through project-based activities.
- AI features: The GoGo Board web app can run user-created AI models in the browser. No AI runs on the GoGo Board hardware itself, and we do not use AI to process user personal data on our servers.

---

## 2. Organization & Responsibility

- Definition: In this policy, "GoGo", "we", "us", and "our" refer collectively to the Teaching and Learning Innovation Center (TLIC) at Chiang Mai University and the Transformative Learning Technologies Lab (TLTL) at Teachers College, Columbia University — the joint operators of the GoGo Board platform.
- Legal entity operating the platform: The GoGo Board platform is jointly operated by two academic institutions acting as joint data controllers:
  - Teaching and Learning Innovation Center (TLIC), Chiang Mai University — Thailand
  - Transformative Learning Technologies Lab (TLTL), Department of Mathematics, Science & Technology, Teachers College, Columbia University — United States
- Data controller contact (primary): support@gogoboard.org
- Mailing addresses:
  - Teaching and Learning Innovation Center (TLIC), Chiang Mai University, 239 Huay Kaew Rd., Suthep, Mueang, Chiang Mai 50200, Thailand
  - Transformative Learning Technologies Lab (TLTL), Department of Mathematics, Science & Technology, Teachers College, Columbia University, 525 West 120th Street, New York, NY 10027, USA

---

## 3. Target Users

- Students (age range, minors Y/N): Ages 10–18+, includes minors (Y). Minors under the identity provider's minimum self-registration age can only access the platform through a parent-supervised or school-issued account.
- Teachers / Instructors: Yes
- School or institutional administrators: Yes
- General public users (if any): Yes, public use allowed

---

## 4. Account & Identity Data Collected

- Required account data: email address, user role (student/teacher/admin). Accounts are created via third-party identity providers (Google or Microsoft); we do not store passwords or operate our own credential system.
- Optional profile data: No other optional profile fields

---

## 5. Learning & Classroom Data

- Types of learning data stored: Source code/block programs, sensor readings and logs (which may be transmitted from the board through the web app or sent directly from the board to our data-logging server when user code enables this), project files, submission timestamps, student notes, teacher feedback, scores received
- Visibility (student / teacher / admin / staff): Student, teacher, and administrator

---

## 6. Device & Hardware Data (GoGo Board)

- Data collected from devices: Board identifier, firmware version, connection status, sensor readings, board state
- Notes / limitations: The GoGo Board connects to user devices via USB or Wi-Fi. When connected to the GoGo web app, the board acts as a peripheral and data flows through the user's browser session. In addition, user-written programs may instruct the board to send or receive data over the internet autonomously — either to a data-logging server we operate, or to third-party servers and devices specified by the user's code. Autonomous data transmission only occurs when explicitly enabled by user code.

---

## 7. Technical & Usage Data

- Automatically collected data: Login timestamps, IP address, browser and operating system information, error/crash logs, basic usage analytics
- Purpose: Platform operation, improvement, and technical support

---

## 8. Data from Minors

- Expected use by minors: Yes (ages 10+)
- Consent mechanism: Account access is provided exclusively through third-party identity providers — currently Google and Microsoft. We do not operate our own account-creation flow. Age verification and, where applicable, parental or guardian consent are handled by the identity provider:
  - Adult users consent on their own behalf when signing in.
  - Minors under the identity provider's minimum age (typically 13 in the United States and Thailand, higher in some other countries) can only access the platform through a parent-supervised account (e.g., Google Family Link, Microsoft Family Safety) or through a school-issued account (e.g., Google Workspace for Education, Microsoft 365 Education), in which case parental or institutional consent has already been collected by the identity provider.
  - Schools and institutions issuing accounts to students through education tenants are responsible for ensuring appropriate parental consent under applicable law.
- Identity data collected from minors: Email address and user role only (same as adult users; no additional data collected from minors)
- Sensitive data collected (Y/N): No sensitive personal data; general location may be inferred from IP address

---

## 9. Purpose of Data Use

- List confirmed purposes and lawful basis for each:
  1. Providing learning services — **Contract**: processing is necessary to deliver the platform service that the user has signed in to use.
  2. Platform improvement — **Legitimate interest**: necessary to maintain, debug, and improve the platform; data is used in aggregated form where possible.
  3. Educational research (anonymized/aggregated) — **Public task / public interest**: research conducted by Chiang Mai University and Columbia University as part of their educational and research missions; data is anonymized or aggregated and any research follows the universities' standard research-ethics review.
  4. Technical support and security — **Legitimate interest**: necessary to provide user support, prevent abuse, and protect the integrity and security of the platform.

---

## 10. User-Generated Content Ownership

- Ownership: Users retain full ownership of their created content (projects, code, programs, data).
- Platform license: We hold a non-exclusive license to display and store user content as needed to operate the service.
- Default visibility: Projects are private by default. Public sharing only occurs when a user takes an explicit action.
- Public sharing methods:
  - Mark project as public: The original project becomes accessible to anyone, and updates remain visible to public viewers. The user can return the project to private at any time.
  - Create public link: A public, read-only snapshot is created at the moment the link is generated. The snapshot is independent of the original and persists indefinitely — it is not affected by later changes or deletion of the original. Users may email support@gogoboard.org to request manual removal of a snapshot.
- Consequences of public sharing: When a user makes a project public by either method, they consent to public access of all content in that project. Public content may be viewed, downloaded, forked, or referenced by anyone. We cannot guarantee the removal of copies already made by others while the content was public.
- Minors: Minors may share projects publicly. They are advised not to include personal information (full name, photograph, voice, school, or location) in publicly shared projects. Schools and institutions managing student accounts may restrict or disable public sharing for their users.

---

## 11. Data Sharing

- Who data is shared with: Identity providers (Google, Microsoft) for authentication, hosting/infrastructure providers, and analytics services. Note: we also operate our own data-logging server that receives data sent directly from GoGo Boards when user-written programs enable this — this is our own infrastructure, not a third party.
- Service providers: Amazon Web Services (AWS), Google (Sign-In and Analytics), Microsoft (Sign-In), and our self-hosted platform analytics.

---

## 12. International Data Storage & Transfer

- Hosting country: The GoGo Board platform is currently hosted in the Asia Pacific (Singapore) AWS region. Some operational data (e.g., analytics, error reports) may be processed by service providers based in other countries.
- Cross-border transfer safeguards: Where personal data is transferred outside Thailand, we rely on the AWS Data Processing Addendum, which incorporates Standard Contractual Clauses recognized as appropriate safeguards under Thailand's PDPA (Section 28) and equivalent frameworks. For analytics services (Google Analytics), we rely on the corresponding processor agreement.
- Future expansion: We may add additional AWS regions in the future (e.g., for users in the Americas). Material changes to hosting locations will be reflected in this policy under §18.

---

## 13. Data Retention

- Retention periods: Account data and associated learning data (projects, sensor logs, etc.) are retained for as long as the account is active, and are deleted on request from the user or their school. We may also, from time to time, delete data associated with long-inactive accounts to minimize the personal data we hold; no fixed schedule is promised.
- Deletion process: Users email support@gogoboard.org to request data deletion.
- Exception — public-link snapshots: Public-link snapshots are stored independently of the originating account and are not automatically removed when the account is deleted. They persist indefinitely unless the user (or other rights-holder) specifically requests their removal by emailing support@gogoboard.org.

---

## 14. User Rights & Controls

- Supported rights: Access, correction, deletion, data export (portability)
- Request process: Submit requests via email to support@gogoboard.org
- Note on public-link snapshots: Account deletion does not automatically remove public-link snapshots created by the user. To request removal of a specific public-link snapshot, include the snapshot URL in a separate request to support@gogoboard.org.

---

## 15. Security Practices

- High-level measures: HTTPS encryption; authentication delegated to third-party identity providers (Google, Microsoft), so we do not store user passwords; access controls; regular backups.
- Breach notification: In the event of a personal data breach, we will notify the relevant data protection authority — in Thailand, the Personal Data Protection Committee (PDPC) — within 72 hours of becoming aware of the breach, where required by applicable law. In the United States, we will notify affected users and applicable state authorities in accordance with the breach notification laws of the relevant state. Affected users will be notified directly when a breach is likely to result in high risk to their rights and freedoms.

---

## 16. Cookies & Tracking

- Cookie usage: Essential cookies (session/authentication) and analytics cookies (used by both Google Analytics and our self-hosted platform analytics).
- Analytics / ads (Y/N): Analytics: Yes — Google Analytics and our self-hosted platform analytics; Advertising: No.
- Cookie consent: On first visit, users are shown a cookie consent banner (pop-up) that allows them to accept or decline non-essential cookies (analytics). Essential cookies required for authentication and session management are always used. Users can change their cookie preferences at any time via a link in the site footer.

---

## 17. Third-Party Links & Integrations

- Identity providers: Google and Microsoft — used for user authentication. Logging in routes the user through the provider's authentication flow; the provider's own privacy policy governs that interaction.
- Analytics: Google Analytics — see §11 and §16.
- Hosting: Amazon Web Services (AWS) — see §11.
- User-initiated integrations: User-written programs running on the GoGo Board may connect to third-party servers, devices, or MQTT brokers specified by the user. These connections are made under the user's own control and are not operated by us. We are not responsible for the privacy practices of any third-party service that a user chooses to connect to.
- Outbound hyperlinks: Documentation and learning materials may link to external resources (e.g., reference documentation, tutorials). We are not responsible for the content or privacy practices of external sites.

---

## 18. Policy Updates

- Acceptance: By signing in to the GoGo Board platform, users acknowledge and agree to this Privacy Policy. The login page displays a clear notice to this effect with a link to the current policy.
- Notification of changes: Updates to the Privacy Policy are posted on the website with an updated effective date. A version history is maintained so users can review what has changed. Where a change materially affects how user data is handled, we will make reasonable efforts to notify users in-app.

---

## 19. Contact Information

- General privacy contact: support@gogoboard.org
- Data Protection Officers (DPOs): We have designated two Data Protection Officers, one for each joint controller:
  - Dr. Arnan Sipitakiat — Chiang Mai University (Thailand)
  - Dr. Paulo Blikstein — Columbia University (United States)
- DPO contact: dpo@gogoboard.org (all DPO-related requests, regardless of jurisdiction, are received at this address and routed to the appropriate DPO)
- Jurisdiction: Thailand (PDPA) and United States privacy laws

---

## 20. Student Privacy Commitments (US Schools)

For students using the GoGo Board through a US school or institution, we make the following commitments in line with US federal and state student-privacy laws (including FERPA, COPPA, California SOPIPA, New York Education Law §2-d, and Illinois SOPPA):

- We do not sell student personal information.
- We do not use student personal information for targeted advertising.
- We do not build non-educational profiles of students.
- We delete student data on request from the school, parent, or student, as described in §13 and §14.
- We maintain reasonable security practices as described in §15.
- We act as a "school official" under FERPA when providing services to US K-12 schools, meaning student data is used only to provide and improve the service for the benefit of the school and its students.
