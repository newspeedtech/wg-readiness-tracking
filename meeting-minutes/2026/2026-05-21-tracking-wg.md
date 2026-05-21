layout: default
title: 2026-05-21 Tracking WG Meeting Record
parent: 2026
grand_parent: Meeting Minutes
---

# Post-Quantum Cryptography Alliance - Readiness Tracking Working Group Meeting 21 May, 2026
[**View Recording**](https://zoom.us/rec/play/PFmj_mBJAtR1KAi03ZHPiSxMNfWknTKUJ4VjCSwDQhQFb_k30ghKhIJBGCYpOMwR1NnKW25MAlsIVWcf.zGCoIjTZZlUeB_JZ?accessLevel=meeting&canPlayFromShare=true&from=share_recording_detail&continueMode=true&oldStyle=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fzoom.us%2Frec%2Fshare%2F6w2izilzQM1o3OKHgXrfJb3UqkS8wR4mDkKwPWUcvTd0xE9lLTS-2NkGuYh6y2Is.j0K9ajdf_akPgmYG) 
*Recordings are also available on your [Open Profile](https://openprofile.dev/my-meetings) page under Past Meetings*  
[**Join the meeting**](https://zoom-lfx.platform.linuxfoundation.org/meeting/92180236021?password%3Db0389cf7-46b4-4b12-8960-743736597cff&sa=D&source=calendar&ust=1779060340269221&usg=AOvVaw0xXXgXsS7I24ZkWvbZYInS)  
[**PQCA Meeting Calendar**](https://pqca.org/calendar/)  
[**Discord Server**](https://discord.pqca.org)

---

### **Antitrust Policy Notice**

Linux Foundation meetings involve participation by industry competitors, and it is the intention of the Linux Foundation to conduct all of its activities in
accordance with applicable antitrust and competition laws. It is therefore extremely important that attendees adhere to meeting agendas, and be aware of,
and not participate in, any activities that are prohibited under applicable US state, federal or foreign antitrust and competition laws. Examples of types
of actions that are prohibited at Linux Foundation meetings and in connection with Linux Foundation activities are described in the Linux Foundation
Antitrust Policy available at [linuxfoundation.org/antitrust-policy](https://linuxfoundation.org/antitrust-policy). If you have questions about these
matters, please contact your company counsel, or if you are a member of the Linux Foundation, feel free to contact Andrew Updegrove of the firm of Gesmer
Updegrove LLP, which provides legal counsel to the Linux Foundation.

---

## Attendance (_Alphabetical by 1st name_)
* [x] Aditya Koranga, NgKore \[TAC Chair\]
* [x] Aleksei Odinokov, PQC Ready
* [x] Andy Warner, Google \[Tracking WG Chair\]
* [x] Avinash Nagadi
* [x] Basil Hess, IBM
* [x] Bill Turner, PKI Consortium
* [x] Christian Pfister, LGT Bank
* [x] Daniel Speciale, QInsight
* [x] Guncha Malik, IBM
* [x] Hart Montgomery, Linux Foundation
* [x] Iyan Mendez Veiga, ? Univesity
* [x] Jane Ginn, Cyber Threat Intelligence Network
* [x] Jeyaganesh Narayanaswamy, AIB (Ireland)
* [x] Kyle Loree, Quantum Algorithms Institute
* [x] Marla Sumner
* [x] Masab Iqbal, Multiverse Computing
* [x] Mukul Kulkarni, Technology Innovation Institute (Abu Dhabi)
* [x] Neha Gupta, University of Surrey
* [x] Salvatore Migliaccio, Namirial
* [x] Shubham Kumar, NgKore
* [x] Sogo Pierre Sanon, Hydro Quebec Research Institute
* [x] Thomas Pöppelmann, Google

---
# Meeting Agenda

- **Intro to the WG**

 - **Goal**: Provide a reliable source of information about the Post-Quantum Cryptography readiness of common devices, libraies, operating systems and software via a community driven effort welcoming submission and updates from any interested party. To succeed, active community participation is needed. 
 - Approved by the TAC: https://github.com/PQCA/TAC/issues/139
 - Mailing List: https://lists.pqca.org/g/wg-readiness-tracking
 - GitHub Repository: https://github.com/PQCA/wg-readiness-tracking
 - Meeting Cadence: Every 2 weeks beginning May 21, 2026 [meeting link] - Open to the public

---

# Discussion & Updates

### **Introductions**

For the first meeting, have all attendees provide a quick intro (name, company / org, why they are interested in the Tracking WG)

We spent the majority of the meeting on intros, but it was time well spent to get a feel for the different perspectives all participants had.
It was great to see a wide cross section of organizations and geographies represented.

We did not have time to dive deeply into the rest of the agenda, but we had general consensus to focus on common cryptographic libraries and tooling first and that using Markdown tables is viable for now. The meeting wrapped up right at time.

---

## Push to next meeting

### **Establishing Priorities**

In order to bootstrap the effort, some details about [common cryptography libraries](https://github.com/PQCA/wg-readiness-tracking/blob/main/cryptography.md) has been
added. Do we want to focus on expanding coverage of crypto libraries or start pages to track other areas from the start?

---

### **Establishing Norms**

How do we want this WG to work?:

  - How should we organize the information?
    - Are there any objections to using Markdown tables?
    - Areas to cover?
      - Proposed: Cryptography Libraries / Tools, Cloud Services, HSMs, Networking Devices, Operating Systems, Software
    - Topic / file naming
    -   Proposed: Use reasonably generic signle words with names lower-cased. (e.g. cryptography.md. cloud.md, hsm.md, networking.md, os.md, software.md) 
    - Do we want the same table format for all areas or should they be customized per tracked area?
  - Code commit rules
    - Proposed: Initially allow commits with a single approval by a second WG participant, but plan to move to requiring two approvals from reviewers representing different companies / orgs. at the start of Q3 2026. 
  - Individual entry requirements
    - Proposed: Keep the format as simple as possible. Only allow links to technical sources, not press releases or marketing materials.   
  - WG Structure

---

### **Next Steps / Action Items**

| Action Item | Owner | Status / Due Date |
|--------------|--------|------------------|
| Add contributions via PRs | All interested parties | Ongoing | 

---

**Adjourned:** 9:30 am PT.
