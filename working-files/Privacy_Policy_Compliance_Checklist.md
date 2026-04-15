# Privacy Policy Compliance Checklist

**Purpose:** Capabilities and processes the GoGo Board privacy policy commits us to. The privacy policy can only honestly be published once the blocking items below actually work.

**Source document:** [GoGo_Board_Privacy_Policy_Source.md](GoGo_Board_Privacy_Policy_Source.md) (v1.0-draft1)

**Status legend:** `[ ]` = to do · `[~]` = partial · `[x]` = done

---

## BLOCKING — must be done before publishing the policy publicly

### B1. User data rights (§13, §14)
The policy promises users can request access, correction, deletion, and export. Needs to actually work.

- [ ] Access request handling — process for a user to request a copy of all data we hold about them.
- [ ] Correction request handling — process for a user to request correction of inaccurate data.
- [ ] Data deletion (account + associated data) — process to delete a user's account and all associated learning data, project files, sensor logs, and analytics records on request.
- [ ] Data export / portability — ability to produce a machine-readable export of a user's projects, code, sensor logs, and account data.
- [ ] Designated handler — named person responsible for receiving and processing requests sent to support@gogoboard.org / dpo@gogoboard.org.
- [ ] Internal response SLA — aim for 30 days to align with PDPA.

*A manual email-driven process is acceptable to start — it just has to actually work.*

### B2. Public-link snapshot removal (§10, §13, §14)
The policy says snapshots can be removed by emailing support. Support must be able to do this.

- [ ] Manual snapshot-removal procedure — operator tool or DB query to remove a public snapshot by URL.
- [ ] Documented internal process — who handles the request, how to verify the requester has rights to it.

### B3. Cookie consent banner (§16)
The policy describes a consent banner with an option to decline analytics cookies. It must exist.

- [ ] Cookie consent banner shown on first visit.
- [ ] Analytics cookies (Google Analytics + self-hosted) do not load until consented.
- [ ] Footer link to change cookie preferences later.

### B4. AWS Service Terms snapshot (§12)
AWS no longer offers a separately-accepted Data Processing Addendum. Data-processing terms and the EU Standard Contractual Clauses are incorporated directly into the AWS Service Terms and apply automatically to every AWS customer — no acceptance step exists. For audit and change-tracking purposes, we still want a record of the terms we are relying on.

**Relevant section:** AWS Service Terms **§1.14 "Data Protection"** is the authoritative clause. Within it:
- §1.14.1 — references the DPA terms for processing Customer Data
- §1.14.3 — Standard Contractual Clauses (Controller-to-Processor and Processor-to-Processor) for cross-border transfers
- §1.14.4 — UK GDPR Addendum and Swiss Addendum

- [ ] Archive a dated copy (PDF or printout) of the current AWS Service Terms — https://aws.amazon.com/service-terms/ — with particular attention to §1.14.
- [ ] Archive dated copies of the SCCs PDFs and the Supplementary Addendum that §1.14 links to.
- [ ] When Thai counsel or auditors ask what we rely on for cross-border transfer, point them to §1.14 of the archived Service Terms.

### B5. DPO contact channel (§19)
The policy lists `dpo@gogoboard.org`. It must be reachable.

- [ ] `dpo@gogoboard.org` email alias set up and delivering to Dr. Arnan and Dr. Paulo.
- [ ] Someone actually monitors the inbox.

### B6. Legal review — Thai PDPA
The policy is written with PDPA-specific language. A Thai-qualified lawyer should confirm before publishing.

- [ ] Thai counsel review of §8 (minor consent), §9 (lawful basis), §12 (cross-border transfer).
- [ ] US counsel review of §8 (COPPA school-consent), §20 (FERPA/SOPIPA/NY 2-d/IL SOPPA posture).

### B7. Publish-time logistics (Header, §18)
- [ ] Set Version to `1.0` (remove `-draft1`).
- [ ] Set Effective date to the actual go-live date.
- [ ] Login-page notice + link to current policy (per §18 acceptance model).
- [ ] Public version history / change log page.

---

## POST-PUBLISH — should exist soon but not blocking launch

### P1. School / institutional controls (§10, §20)
Promised but not urgent if no school is actively asking for them yet.

- [ ] Admin control to restrict or disable public sharing for users under a school.
- [ ] Bulk deletion / offboarding — delete all student data when a school leaves.
- [ ] Consent-confirmation record at school onboarding.

### P2. Board messaging and data-logging server documentation (§5, §6, §11)
GoGo operates two separate board-facing services that need to be documented:

- **Data-logging server** — receives and *stores* sensor data sent directly from boards when user code enables it.
- **Messaging service** — relays messages between boards in real time and does *not* store them.

- [ ] Written inventory of both services — what data flows through each, access controls, and (for the data-logging server) retention.
- [ ] Retention policy for logged sensor data on the data-logging server (e.g., delete logs older than X months unless attached to an active project). Not applicable to the messaging service, which does not store messages.
- [ ] User-visible indicator in the web app when a program is actively transmitting to either the messaging or the data-logging service.
- [ ] User-facing docs explaining when messaging/logging is active and how to avoid using it.

### P3. Analytics configuration (§16)
- [ ] Google Analytics: confirm IP anonymization on, ad personalization off, data sharing appropriate for minors.
- [ ] Self-hosted analytics: document what it collects, where stored, retention.

### P4. Sub-processor list (§11)
- [ ] Internal list of every third party that touches user data (AWS, Google, Microsoft, self-hosted MQTT).
- [ ] Published externally (optional, but good trust signal for schools).

### P5. Security practices (§15)
- [ ] HTTPS enforced everywhere (including MQTTS / TLS on the MQTT broker).
- [ ] Role-based access controls for GoGo team members who can access user data.
- [ ] Backup policy documented — frequency, retention, encryption at rest, restore-tested.
- [ ] Incident response plan — written process for breach handling with PDPA 72-hour awareness.

### P6. Policy lifecycle ops (§18)
- [ ] Annual policy review on calendar.
- [ ] Trigger for review when data flows change (new IdP, new processor, new data type, new jurisdiction).
- [ ] Material-change notification mechanism (banner on login, email to school admins).

### P7. Joint-controller data-sharing addendum
- [ ] Supplement the CMU ↔ Columbia MoU with a short data-sharing agreement covering who handles user requests, who notifies regulators on breach, who is primary contact.

### P8. Request log
- [ ] Internal log of privacy requests received, actions taken, date completed — useful for audits.

---

## Already done (via source-doc edits)

- [x] §15 corrected: no "secure password storage" claim (we don't store passwords).
- [x] Cross-border transfer documented (§12 — Singapore, AWS DPA, SCCs).
- [x] Lawful basis stated for each purpose (§9).
- [x] Breach notification clause (§15).
- [x] DPOs named (§19).
- [x] Joint controllers identified with addresses (§2).
- [x] Student privacy commitments section added (§20).
- [x] Cookie consent *mechanism* described in the policy (§16) — the UI itself is in B3.
- [x] Retention approach described (§13) — indefinite-until-requested + discretionary cleanup.
- [x] Public-link snapshot behavior disclosed (§10, §13, §14).

---

## Recommended blocking-item priority

1. **B4 — AWS DPA** (5 minutes, already have instructions).
2. **B5 — DPO email alias** (IT task, quick).
3. **B1 — Data rights process** (the big one — document the manual email-driven workflow, even if everything else is manual).
4. **B2 — Snapshot removal procedure** (small but specific commitment; 1 engineer-hour to script).
5. **B3 — Cookie consent banner** (engineering work — use an off-the-shelf library, ~1–2 days).
6. **B6 — Legal reviews** (Thai counsel in particular; can run in parallel with B1–B5).
7. **B7 — Publish-time logistics** (last, once B1–B6 are green).
