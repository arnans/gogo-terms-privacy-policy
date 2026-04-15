# Terms of Use Compliance Checklist

**Purpose:** Capabilities, pages, and processes the GoGo Board Terms of Use commits us to. The ToU can only honestly be published once the blocking items below actually exist.

**Source document:** [GoGo_Board_Terms_of_Use_Source.md](GoGo_Board_Terms_of_Use_Source.md) (v1.0-draft1)

**Status legend:** `[ ]` = to do · `[~]` = partial · `[x]` = done

---

## BLOCKING — must be done before publishing the Terms of Use publicly

### B1. Third-party attribution page (§10)
The ToU says attributions and license texts for third-party open-source libraries are available at a linked URL. The page must exist and the URL must be filled into §10.

- [ ] Create a public attribution / acknowledgments page listing third-party open-source libraries used in the GoGo Board web app and firmware, along with their licenses (e.g., `/licenses` or `/acknowledgments`, or a `THIRD_PARTY_NOTICES.md` served from the site).
- [ ] Confirm the page is reachable from a stable URL before publishing the ToU.
- [ ] Replace the `**TODO:** [attribution page URL]` placeholder in §10 with the real URL.

### B2. Privacy Policy URL (§12)
The ToU references the Privacy Policy at `https://www.gogoboard.org/privacy`. That URL must resolve to the published policy before the ToU goes live.

- [ ] Publish the Privacy Policy (or set up a redirect) at `https://www.gogoboard.org/privacy` so the link in §12 resolves.

### B3. Terms of Use URL
The Terms of Use will be published at `https://www.gogoboard.org/terms`. That URL should be set up as the canonical public location (or redirect) for the document.

- [ ] Publish the Terms of Use (or set up a redirect) at `https://www.gogoboard.org/terms`.

### B4. DMCA Designated Agent operational setup (§18)
The ToU names a Designated DMCA Agent at TLTL (Teachers College, Columbia University) for receiving copyright infringement notices. For the §18 clause to have legal effect under the US DMCA safe harbor, the following must be in place:

- [ ] Obtain a phone number for the DMCA agent from Dr. Paulo Blikstein (required by the US Copyright Office registration and by §18 of the ToU). Replace the `**TODO:**` placeholder in §18 with the number.
- [ ] Set up the `dmca@gogoboard.org` mailbox and confirm it is monitored by (or forwarded to) Dr. Paulo Blikstein or his designee.
- [ ] Register the Designated DMCA Agent with the US Copyright Office DMCA Designated Agent Directory (https://dmca.copyright.gov/). $6 filing fee; registration is valid for 3 years and must be renewed. Register Paulo Blikstein by name, with the title "Designated DMCA Agent" and the TLTL contact details.
- [ ] Establish an internal procedure for receiving, reviewing, and acting on DMCA takedown notices and counter-notices, including a log of notices received and actions taken.

### B5. Content removal and account-suspension capability (§6, §7, §17)
The ToU states we may remove content that violates the Terms (including images, project files, and other user-uploaded materials) and may suspend or terminate accounts. These capabilities must actually be available to operators.

- [ ] Operator tool or documented manual procedure for removing user-uploaded content (projects, images, display media, Classroom materials).
- [ ] Operator tool or documented manual procedure for suspending and terminating accounts.
- [ ] Internal process for reviewing reports of prohibited content or conduct, including who decides, how decisions are recorded, and how affected users are notified.

### B6. Terms of Use update notification (§13)
The ToU commits us to communicating material changes through the service or by email where appropriate.

- [ ] Mechanism for displaying an in-service notice when the ToU changes.
- [ ] Mechanism (or confirmation of existing email capability) to notify registered users about material changes.
- [ ] Maintained version history or changelog of the ToU, with the updated effective date shown on each revision.

### B7. Hardware safety instructions (§9)
The ToU states that users must follow safety instructions provided with the hardware and curriculum materials. Those instructions must actually exist and be current.

- [ ] Confirm that printed or packaged safety instructions ship with (or are readily available for) the GoGo Board hardware.
- [ ] Confirm that online or in-Classroom safety instructions are accessible as part of curriculum materials.
- [ ] Ensure instructions remain current as hardware revisions occur.

---

## Ongoing operational awareness

(These are not pre-publication blockers, but are commitments made by the ToU that shape how we operate going forward.)

### O1. Research ethics compliance (§7)
The ToU permits analysis of user-project content in aggregated or anonymized form for research into educational technology. Performing actual research on user content requires institutional ethics approvals.

- Obtain IRB approval from Teachers College (Columbia University) and/or ethics approval from Chiang Mai University before conducting research that uses user-project content.
- Maintain a log of approved research uses and the institutional approvals on file.

### O2. Retroactive Classroom CC BY consent (§7)
The ToU establishes that educator-created Classroom materials are published under CC BY, with acceptance occurring when educators accept the Terms. Educators who created Classroom lessons before the ToU publication date have not yet agreed to this license.

- Before the ToU takes effect, decide how to handle existing Classroom content: (a) require re-acceptance of the Terms on next login, (b) notify existing educators individually, or (c) confirm that any prior Classroom terms are compatible.

---

## See also

Items related to account deletion, data export, correction, and user-data handling are covered in [Privacy_Policy_Compliance_Checklist.md](Privacy_Policy_Compliance_Checklist.md). The ToU §17 ("You may request deletion of your account as described in the Privacy Policy") and §7 (removal of content) rely on those capabilities being in place.

