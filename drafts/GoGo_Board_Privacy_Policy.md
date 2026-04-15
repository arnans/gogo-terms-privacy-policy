# GoGo Board — Privacy Policy

**Version:** 1.0 (Draft 1)
**Effective date:** Pending — this document is a draft and is not yet binding.

---

## 1. Platform Overview

The GoGo Board is an education-focused hardware and software platform for STEM learning, enabling students to learn programming, sensors, robotics, IoT, and basic AI through project-based activities. You can reach the platform at https://www.gogoboard.org and https://code.gogoboard.org.

The GoGo Board web app can run user-created AI models in the browser. No AI runs on the GoGo Board hardware itself, and we do not use AI to process user personal data on our servers.

---

## 2. Organization & Responsibility

In this policy, "GoGo", "we", "us", and "our" refer collectively to the Teaching and Learning Innovation Center (TLIC) at Chiang Mai University and the Transformative Learning Technologies Lab (TLTL) at Teachers College, Columbia University — the joint operators of the GoGo Board platform.

The platform is jointly operated by two academic institutions acting as joint data controllers:

- Teaching and Learning Innovation Center (TLIC), Chiang Mai University — Thailand
- Transformative Learning Technologies Lab (TLTL), Department of Mathematics, Science & Technology, Teachers College, Columbia University — United States

**Data controller contact:** support@gogoboard.org

**Mailing addresses:**

- Teaching and Learning Innovation Center (TLIC), Chiang Mai University, 239 Huay Kaew Rd., Suthep, Mueang, Chiang Mai 50200, Thailand
- Transformative Learning Technologies Lab (TLTL), Department of Mathematics, Science & Technology, Teachers College, Columbia University, 525 West 120th Street, New York, NY 10027, USA

---

## 3. Target Users

The GoGo Board platform is used by:

- **Students**, ages 10–18+ (includes minors). Minors under the identity provider's minimum self-registration age can only access the platform through a parent-supervised or school-issued account.
- **Teachers and instructors**
- **School and institutional administrators**
- **General public users** (public use is allowed)

---

## 4. Account & Identity Data Collected

When you sign in to the GoGo Board platform, we collect:

- **Required:** email address, user name (as provided by the identity provider), and user role (student / teacher / admin).

Accounts are created via third-party identity providers (Google or Microsoft); we do not store passwords or operate our own credential system. We do not collect optional profile fields beyond what is listed above.

---

## 5. Learning & Classroom Data

As you use the platform, we store data related to your learning activities. This includes:

- Source code and block programs
- Sensor readings and logs, which may be transmitted from the board through the web app or sent directly from the board to our data-logging server when user code enables this
- Project files
- Submission timestamps
- Student notes
- Teacher feedback
- Scores received
- Classroom lesson progress and completion records

This learning data is visible to the student, teacher, and administrator roles as appropriate.

---

## 6. Device & Hardware Data (GoGo Board)

When you connect a GoGo Board to the platform, we may collect:

- Board identifier
- Firmware version
- Connection status
- Sensor readings
- Board state

The GoGo Board connects to user devices via USB or Wi-Fi. When connected to the GoGo web app, the board acts as a peripheral and data flows through the user's browser session. Where user-written programs cause the board to transmit data autonomously (e.g., to a logging or messaging service), see Section 11 for the data-sharing details.

---

## 7. Technical & Usage Data

We automatically collect technical information as you use the platform, including:

- Login timestamps
- IP address
- Browser and operating system information
- Error and crash logs
- Basic usage analytics

This data is used for platform operation, improvement, and technical support.

---

## 8. Data from Minors

The platform is designed to be used by minors (ages 10+).

**Consent mechanism.** Account access is provided exclusively through third-party identity providers — currently Google and Microsoft. We do not operate our own account-creation flow. Age verification and, where applicable, parental or guardian consent are handled by the identity provider:

- Adult users consent on their own behalf when signing in.
- Minors under the identity provider's minimum age (typically 13 in the United States and Thailand, higher in some other countries) can only access the platform through a parent-supervised account (e.g., Google Family Link, Microsoft Family Safety) or through a school-issued account (e.g., Google Workspace for Education, Microsoft 365 Education), in which case parental or institutional consent has already been collected by the identity provider.
- Schools and institutions issuing accounts to students through education tenants are responsible for ensuring appropriate parental consent under applicable law.

**Data collected from minors.** Email address, user name, and user role only — the same data we collect from adult users. We do not collect additional data from minors.

**Sensitive data.** We do not collect sensitive personal data. General location may be inferred from IP address.

---

## 9. Purpose of Data Use

We use your personal data for the following purposes, with the lawful basis for each:

1. **Providing learning services** — *Contract*: processing is necessary to deliver the platform service that the user has signed in to use.
2. **Platform improvement** — *Legitimate interest*: necessary to maintain, debug, and improve the platform; data is used in aggregated form where possible.
3. **Educational research** (anonymized or aggregated) — *Public task / public interest*: research conducted by Chiang Mai University and Columbia University as part of their educational and research missions; data is anonymized or aggregated and any research follows the universities' standard research-ethics review.
4. **Technical support and security** — *Legitimate interest*: necessary to provide user support, prevent abuse, and protect the integrity and security of the platform.

---

## 10. User-Generated Content Ownership

**Ownership.** Users retain full ownership of their created content (projects, code, programs, data).

**Platform license.** We hold a non-exclusive license to display and store user content as needed to operate the service.

**Default visibility.** Projects are private by default. Public sharing only occurs when a user takes an explicit action. There are two methods for sharing a project publicly:

- **Mark project as public.** The original project becomes accessible to anyone, and updates remain visible to public viewers. The user can return the project to private at any time.
- **Create public link.** A public, read-only snapshot is created at the moment the link is generated. The snapshot is independent of the original and persists indefinitely — it is not affected by later changes or deletion of the original. Users may email support@gogoboard.org to request manual removal of a snapshot.

**Consequences of public sharing.** When a user makes a project public by either method, they consent to public access of all content in that project. Public content may be viewed, downloaded, forked, or referenced by anyone. We cannot guarantee the removal of copies already made by others while the content was public.

**Minors.** Minors may share projects publicly. They are advised not to include personal information (full name, photograph, voice, school, or location) in publicly shared projects. Schools and institutions managing student accounts may restrict or disable public sharing for their users.

---

## 11. Data Sharing

We share or route data through the following categories of recipients:

**Third-party service providers.** Identity providers (Google, Microsoft) for authentication; hosting and infrastructure (Amazon Web Services); and analytics services (Google Analytics). We also use our own self-hosted platform analytics.

**Our own infrastructure.** A data-logging server that receives and stores sensor data sent directly from GoGo Boards, and a messaging service that relays messages between GoGo Boards in real time without storing them. Both services are operated by us, not by third parties.

**User-specified third parties.** When user-written programs instruct the board to connect to other servers, devices, or messaging services, data flows to those endpoints as well. Those destinations are not operated or controlled by us (see Section 17).

**Autonomous transmission** from the board only occurs when explicitly enabled by user code.

---

## 12. International Data Storage & Transfer

**Hosting country.** The GoGo Board platform is currently hosted in the Asia Pacific (Singapore) AWS region. Some operational data (e.g., analytics, error reports) may be processed by service providers based in other countries.

**Cross-border transfer safeguards.** Where personal data is transferred outside Thailand, we rely on the data-processing terms in the AWS Service Terms, which automatically incorporate the European Commission's Standard Contractual Clauses. These are recognized as appropriate safeguards under Thailand's PDPA (Section 28) and equivalent frameworks. For analytics services (Google Analytics), we rely on the corresponding processor agreement.

**Future expansion.** We may add additional AWS regions in the future (e.g., for users in the Americas). Material changes to hosting locations will be reflected in this policy under Section 18.

---

## 13. Data Retention

Account data and associated learning data (projects, sensor logs, etc.) are retained for as long as the account is active, and are deleted on request from the user or their school. We may also, from time to time, delete data associated with long-inactive accounts to minimize the personal data we hold; no fixed schedule is promised.

To request deletion of your account and data, email support@gogoboard.org.

**Exception — public-link snapshots.** Public-link snapshots are stored independently of the originating account and are not automatically removed when the account is deleted. They persist indefinitely unless the user (or other rights-holder) specifically requests their removal by emailing support@gogoboard.org.

---

## 14. User Rights & Controls

You have the following rights with respect to your personal data: **access, correction, deletion, and data export (portability).**

To exercise these rights, email your request to support@gogoboard.org.

**Note on public-link snapshots.** Account deletion does not automatically remove public-link snapshots created by the user. To request removal of a specific public-link snapshot, include the snapshot URL in a separate request to support@gogoboard.org.

---

## 15. Security Practices

We use HTTPS encryption for data in transit. Authentication is delegated to third-party identity providers (Google, Microsoft), so we do not store user passwords. We apply access controls and perform regular backups.

**Breach notification.** In the event of a personal data breach, we will notify the relevant data protection authority — in Thailand, the Personal Data Protection Committee (PDPC) — within 72 hours of becoming aware of the breach, where required by applicable law. In the United States, we will notify affected users and applicable state authorities in accordance with the breach notification laws of the relevant state. Affected users will be notified directly when a breach is likely to result in high risk to their rights and freedoms.

---

## 16. Cookies & Tracking

The platform uses:

- **Essential cookies** (session and authentication)
- **Analytics cookies** (used by both Google Analytics and our self-hosted platform analytics)

We do not use cookies for advertising.

**Cookie consent.** On first visit, users are shown a cookie consent banner that allows them to accept or decline non-essential cookies (analytics). Essential cookies required for authentication and session management are always used. Users can change their cookie preferences at any time via a link in the site footer.

---

## 17. Third-Party Links & Integrations

**Identity providers.** Google and Microsoft — used for user authentication. Logging in routes the user through the provider's authentication flow; the provider's own privacy policy governs that interaction.

**Analytics.** Google Analytics — see Sections 11 and 16.

**Hosting.** Amazon Web Services (AWS) — see Section 11.

**User-initiated integrations.** User-written programs running on the GoGo Board may connect to third-party servers, devices, or messaging services specified by the user. These connections are made under the user's own control and are not operated by us. We are not responsible for the privacy practices of any third-party service that a user chooses to connect to.

**Embedded video.** Some Classroom lessons include videos embedded from third-party platforms such as YouTube. Embedded video players may set cookies or collect browser data (e.g., IP address, user agent) under the video platform's own privacy practices, even before a user interacts with the video. The video platform's privacy policy governs that data; we do not control or receive it.

**Outbound hyperlinks.** Documentation and learning materials may link to external resources (e.g., reference documentation, tutorials). We are not responsible for the content or privacy practices of external sites.

---

## 18. Policy Updates

**Acceptance.** By signing in to the GoGo Board platform, users acknowledge and agree to this Privacy Policy, together with the GoGo Board Terms of Use (available at https://www.gogoboard.org/terms). The login page displays a clear notice to this effect with a link to the current policy.

**Notification of changes.** Updates to the Privacy Policy are posted on the website with an updated effective date. A version history is maintained so users can review what has changed. Where a change materially affects how user data is handled, we will make reasonable efforts to notify users in-app.

---

## 19. Contact Information

**General privacy contact:** support@gogoboard.org

**Data Protection Officers (DPOs).** We have designated two Data Protection Officers, one for each joint controller:

- Dr. Arnan Sipitakiat — Chiang Mai University (Thailand)
- Dr. Paulo Blikstein — Columbia University (United States)

**DPO contact:** dpo@gogoboard.org (all DPO-related requests, regardless of jurisdiction, are received at this address and routed to the appropriate DPO).

**Jurisdiction.** This policy is drafted with reference to Thailand (PDPA) and United States privacy laws.

---

## 20. Student Privacy Commitments (US Schools)

For students using the GoGo Board through a US school or institution, we make the following commitments in line with US federal and state student-privacy laws (including FERPA, COPPA, California SOPIPA, New York Education Law §2-d, and Illinois SOPPA). These commitments apply to student personal information and to educational records (such as Classroom lesson progress, scores, student notes, and teacher feedback):

- We do not sell student personal information.
- We do not use student personal information for targeted advertising.
- We do not build non-educational profiles of students.
- We delete student data on request from the school, parent, or student, as described in Sections 13 and 14.
- We maintain reasonable security practices as described in Section 15.
- We act as a "school official" under FERPA when providing services to US K-12 schools, meaning student data is used only to provide and improve the service for the benefit of the school and its students.
