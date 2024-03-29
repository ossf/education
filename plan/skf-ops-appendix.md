# SKF-OPS Appendix

This appendix details plans for the managemnt & maintenance of the Security KNowledge Framework platform, which is integral to the EDU.SIG's plan to priovide educational materials to all learners.

**Legend**:

✅ = Work to be completed by SKF Ops Team

🤝 = Work to be assisted by SKF Ops Team

⛔ = Work cannot be completed by SKF Ops Team

## 2.1 Goal: SKF Ops Team

The primary objective of the Security Knowledge Framework (SKF) Operations Team is to ensure that SKF survives the test of time and is freely available for generations of Security learning

### Maintenanace / OPS

- **OPS1**: Git Repository

  - Review current 'Lab' contribution procedures
  - Anything merged into the SKF repository will become the responsibly of the SKF Operations team.
  - Information that is no longer factual will either be updated or retired by the SKF Operations team.
  - Contributions to the SKF repository shall be reviewed and merged in a timely manner by SKF Operations team.
  - SKF Operations team will provide Github workflows for smooth contributions and expectation management.
  - Contributions that do not adhere to SKF Contribution Guidelines, shall be given assistance or clear instructions on what needs to be rectified.
  - SKF Operations shall maintain a CodeSpaces Developer configuration to ease contributions to SKF.

- **OPS2**: CI/CD

  - The SKF application with all the components will be fully automated and shall be carried out by SKF Operations team.
  - Ongoing improvement and maintenance of CI/CD pipelines shall be carried out by SKF Operations team.
  - SKF Operations team will create code/language quality checks for maintainability and performance.

- **OPS3**: Security
  - SKF Operations will handle any Security Incidents.
  - SKF Operations team will perform secure code reviews on the PR's
  - SKF Operations team will perform security penetration tests on the PR's
  - SKF Operations team will integrate security test automation in the CI/CD pipeline
    - SAST
    - SCA
    - Start a bug bounty program (TBD what platform)
- **OPS4**: Infra Maintenance

  - Cloud Operations
  - Make sure that SKF Cloud services remain operational.
  - Make sure that the SKF Platform runs within its allocated budget.

- **OPS5**: Services
  - Make sure that SKF System services remain operational and up-to-date.
- **OPS6**: Information gathering
  - APM
  - Analytics
  - Security and event monitoring

### Steward

- **OPS7**: API Development
  - SKF Operations will architect, develop, and maintain all SKF APIs offered.
- **OPS8**: UI/UX
  - SKF Operations will design, maintain, and continuously improve the SKF Platform's UI/UX.
- **OPS9**: Feedback
  - SKF Operations will ensure that community feedback is consistently prioritized.
  - SKF Operations shall work with the Education SIG as it's primary channel for community feedback.
- **OPS10**: Content quality

  - SKF Operations shall work with the content providers/donators for improving the source materials when possible gaps in materials are identified.
  - SKF Operations shall work with the content providers/donators to make sure the hands-on labs are correctly being set up and are the level of quality we desire.

- **OPS11**: Organize
  - Bi-weekly public meetings where we prioritise the work to be executed
  - Executive meetings (Stakeholders, Team Lead, Architect) for roadmap & strategic discussions
  - Active in the Slack, Gitter, Discord channels to address the questions of the users related to the SKF features, material information and Labs. Live support channel.

## Team

### Project management

- _Project Lead - Mission, vision, strategy_
- _Project Lead - Quality Assurance_
- _Project Lead - Architect_

### Lead Developer

- Full Stack Developer

### Development Team

- Full Stack Developer
- Full Stack Developer

### Design Team

- UX Designer

### Platform Team

- DevOps Engineer

### Time & Resource Estimate

> **TOTAL**: 8 x Full-time for year 1
> **TOTAL**: 65k Infrastructure cost

---

## 2.2 Goal: Refactor 'Lab' contribution procedures

We want to make new contributions to the SKF Labs as smoothly as possible but also make sure we have high-quality materials being pushed

### Key Steps/Milestones

- **M1**: Publish updated 'Lab' and 'Content' contribution procedures
  - [ ] Review currently established 'Lab' contribution procedures
  - [ ] Refactor 'Lab' contribution procedures into a 'Lab/Write-up Style Guide' document
  - [ ] Publish 'Lab/Write-up Style Guide' document

### Time & Resource Estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ✅    |       -       |      80       | Year 1 |

> **SKF OPS TEAM - TOTAL**: 80 hours

---

## 2.3 Expand current 'Lab' offerings that correlate to the currently indexed Security Knowledge Graph (SKG) 'Standards'

Expand current 'Labs' offerings to complete SKF's coverage with the currently indexed standards (e.g., ASVS & WSTG) in the Security Knowledge Graph (SKG)

In the Security Knowledge Framework (SKF), we define a 'Lab' as an isolated web application environment demonstrating a specific Security vulnerability/concept. Each 'Lab' also details how to exploit and fix the said vulnerability/concept in an accompanying 'Write-up' markdown file. Each 'Write-up' should be authored in accordance with the SKF 'Lab/Write-up Style Guide'.

### Key Steps/Milestones

- **M1**: Improving the current 'Lab' offering to cover the currently indexed standards (e.g., ASVS & WSTG) in the Security Knowledge Graph (SKG)

  - Python
    - [ ] Create **[180 Labs]** new Python labs
    - [ ] correlate new Python 'Labs' to 'Concepts'
  - Java
    - [ ] Create **[180 Labs]** new Java labs
    - [ ] correlate new Java 'Labs' to 'Concepts'
  - Nodejs
    - [ ] Create **[180 Labs]** new NodeJS labs
    - [ ] correlate new NodeJS 'Labs' to 'Concepts'

- **M2**: Create job descriptions for contractors for M3

  - [ ] Create a job description for secdev contributor per program language
  - [ ] Get feedback on the job description
  - [ ] post opening and interview candidates
  - [ ] onboard secdev contributors

- **M3**: Extending current 'Lab' offerings to include 5 other languages for the currently indexed standards (e.g., ASVS & WSTG) in the Security Knowledge Graph (SKG)

  - Ruby
    - [ ] Create **[280 Labs]** new Ruby labs
    - [ ] Correlate new Ruby 'Labs' to 'Concepts'
  - Rust
    - [ ] Create **[280 Labs]** new Rust labs
    - [ ] Correlate new Rust 'Labs' to 'Concepts'
  - Go
    - [ ] Create **[280 Labs]** new Go labs
    - [ ] Correlate new Go 'Labs' to 'Concepts'
  - DotNet/C#
    - [ ] Create **[280 Labs]** new DotNet/C# labs
    - [ ] Correlate new DotNet/C# 'Labs' to 'Concepts'
  - C/C++
    - [ ] Create **[280 Labs]** new C/C++ labs
    - [ ] Correlate new C/C++ 'Labs' to 'Concepts'

### Budget Requests

### Time & Resource Estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate  |   Year   |
| :-------: | :-----: | :-----------: | :------------: | :------: |
|  **M1**   |   ✅    |       -       |    4320hrs     |  Year 1  |
|  **M2**   |   ✅    |       -       |     50hrs      |  Year 1  |
|  **M3**   |   🤝    |       5       | 2240hrs (each) | Year 1~2 |

- Each new 'Lab' is expected to take about ~8 hours to develop.

> **CONTRACTOR - TOTAL**: 11200 hours
> **SKF OPS TEAM - TOTAL**: 4570 SKF Ops hours

---

## 2.4 Goal: Create new 'Labs' that correlate to OpenSSF's Secure Development Fundamentals course

Create new 'Labs' offerings to complete SKF's coverage with the OpenSSF's Secure Development Fundamentals course in the Security Knowledge Graph (SKG)

In the Security Knowledge Framework (SKF), we define a 'Lab' as an isolated web application environment demonstrating a specific Security vulnerability/concept. Each 'Lab' also details how to exploit and fix the said vulnerability/concept in an accompanying 'Write-up' markdown file. Each 'Write-up' should be authored in accordance with the SKF 'Lab/Write-up Style Guide'.

### Key Steps/Milestones

- **M1**: Perform gap analysis from the current SKF 'Lab' offering (including the work already performed in 2.3 Goal)

  - [ ] Perform gap analysis

- **M2**: Create job descriptions for contractors for M3

  - [ ] Create a job description for secdev contributor per program language
  - [ ] Get feedback on the job description
  - [ ] post opening and interview candidates
  - [ ] onboard secdev contributors

- **M3**: Extending current 'Lab' offerings to include all current programming languages for the OpenSSF's Secure Development Fundamentals course in the Security Knowledge Graph (SKG)

  - Python
    - [ ] Create **[30 Labs +/- ]** new Python labs
    - [ ] Correlate new Python 'Labs' to 'Concepts'
  - Java
    - [ ] Create **[30 Labs +/- ]** new Java labs
    - [ ] Correlate new Java 'Labs' to 'Concepts'
  - Nodejs
    - [ ] Create **[30 Labs +/- ]** new NodeJS labs
    - [ ] Correlate new NodeJS 'Labs' to 'Concepts'
  - Ruby
    - [ ] Create **[30 Labs +/- ]** new Ruby labs
    - [ ] Correlate new Ruby 'Labs' to 'Concepts'
  - Rust
    - [ ] Create **[30 Labs +/- ]** new Rust labs
    - [ ] Correlate new Rust 'Labs' to 'Concepts'
  - Go
    - [ ] Create **[30 Labs +/- ]** new Go labs
    - [ ] Correlate new Go 'Labs' to 'Concepts'
  - DotNet/C#
    - [ ] Create **[30 Labs +/- ]** new DotNet/C# labs
    - [ ] Correlate new DotNet/C# 'Labs' to 'Concepts'
  - C/C++
    - [ ] Create **[30 Labs +/- ]** new C/C++ labs
    - [ ] Correlate new C/C++ 'Labs' to 'Concepts'

### Time & Resource Estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |   Year   |
| :-------: | :-----: | :-----------: | :-----------: | :------: |
|  **M1**   |   ✅    |       -       |     40hrs     |  Year 1  |
|  **M2**   |   ✅    |       -       |     80hrs     |  Year 1  |
|  **M3**   |   🤝    |       8       | 240hrs (each) | Year 1~2 |
|  **M4**   |   ✅    |       -       | 24hrs (each)  | Year 1~2 |

The Key Steps/Milestones is an indication and educated guess of the amount of missing 'Labs'.
Remark: The number of hours might be less is than we assume.

- Each new 'Lab' is expected to take about ~8 hours to develop.

> **CONTRACTOR - TOTAL**: 1920 hours
> **SKF OPS TEAM - TOTAL**: 372 hours

---

## 2.5 Goal: Update the currently indexed standards (e.g., (m)ASVS & WSTG, PCI-DSS and the course: OpenSSF Security Fundamentals) in the Security Knowledge Graph (SKG) in an automated fashion

We want to facilitate new updates of the materials as smoothly as possible by creating automatic CI/CD actions so they can be consumed into SKF and the SKG component

### Key Steps/Milestones

- **M1**: Create per standard and/or course an automated action for pulling in updates
  - [ ] OpenSSF Security Fundamental Course creates CI/CD ingestion action to SKF & SKG
  - [ ] ASVS create CI/CD ingestion action to SKF & SKG
  - [ ] WSTG create CI/CD ingestion action to SKF & SKG
  - [ ] MASVS create CI/CD ingestion action to SKF & SKG
  - [ ] PCI-DSS create CI/CD ingestion action to SKF & SKG

### Time & Resource Estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ✅    |       -       | 60hrs (each)  | Year 1 |

> **SKF OPS TEAM - TOTAL**: 300 SKF Ops Hours

---

## 2.6 Goal: Create Quizzes & Tests for currently indexed standards (e.g., (m)ASVS & WSTG, PCI-DSS and the course: OpenSSF Security Fundamentals) in the Security Knowledge Graph (SKG)

Currently, SKF doesn't have any quizzes or tests implemented in SKG Database or Web for any of the currently indexed content

(Consider paying special attention to prevent certain users trying to game the system.)

Note: Integration with LFX platform

### Key Steps/Milestones

- **M1**: Design UI/UX for Quizzes & Tests Area
  - [ ] Determine extent of integration possible with LFX platform
  - [ ] Prototype the Quizzes & Tests area of the SKG Web on Figma.
- **M2**: Implement Quizes & Tests in SKG Database
  - [ ] ASVS / WSTG
  - [ ] OpenSSF Security Fundamentals

(Some of course, such as the OpenSSF Security Fundamentals, already have pre-existing quizzes/tests that only need to implemented in SKG.)

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|    M1     |   ✅    |       -       |     80hrs     | Year 1 |
|    M2     |   ✅    |       -       |  40hrs(each)  | Year 1 |

> **SKF OPS TEAM - TOTAL**: 160 hours

---

## 2.7 Goal: Alternate delivery streams for content

Sponsor existing or create alternate delivery streams for educational content

### Key Steps/Milestones

- **M1**: Establish a job description for an educational content developer.

  - [ ] Create a job description for an educational content developer
  - [ ] Get feedback on the job description
  - [ ] post opening and interview candidates
  - [ ] onboard secdev contributors

- **M2**: Create a calendar of conferences where our content would be useful to train

  - [ ] Identify potential conferences where we want to present the materials and platform
  - [ ] Contact conferences and apply for CFP / CFT
  - [ ] Create a calendar of selected conferences

- **M3**: Creation of training slides

  - [ ] Create a "Bootcamp" slide deck for using as delivery method for in-person trainings
  - [ ] Deliver two "Bootcamps" at LF-sponsored conferences based on existing Secure Development Fundamentals class

- **M4**: Creation of materials for other channels

  - [ ] Deliver twelve "thought leadership" secure development blogs
  - [ ] Deliver 2 secure development OSSF webinars

#### Time & Resource Estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ✅    |       -       |     10hrs     | Year 1 |
|  **M2**   |   ⛔    |       1       |     40hrs     | Year 1 |
|  **M3**   |   🤝    |       -       |    180hrs     | Year 1 |
|  **M4**   |   ⛔    |       1       |    160hrs     | Year 1 |

> **CONTRACTOR - TOTAL**: 380 hours
> **SKF OPS TEAM - TOTAL**: 80 hours

Y1 - Hire Education Content Developer (1 person x $ 300K): $ 300K

---

### 2.7.1: Educational content development and management of blogs, webinars, podcasts

We want to create different delivery methods for the materials we have to also reach other types of persona's using blogs, podcasts and webinars

#### Key Steps/Milestones

- **M1**: Identification of the different channels of the delivery of materials

  - [ ] Identify and select channels content will be delivered in
  - [ ] Create a roadmap for content creation and publication

- **M2**: Create content for channels

  - [ ] Identify and select channels content will be delivered in
  - [ ] Develop in-person educator-led variations of training materials (e.g., with hands-on lab work) & go to conferences to encourage training

#### Time & resource estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ⛔    |       1       |     80hrs     | Year 1 |
|  **M3**   |   ⛔    |       1       |    640hrs     | Year 1 |

> **CONTRACTOR - TOTAL**: 720 hours

---

### 2.7.2: Expand Secure Development thought leadership through blogs, webinars, podcasts

Many traditional channels are available to augment traditional classes such as podcasts, blogs, and webinars. These are generally inexpensive and readily-accessible tools to amplify the awareness of key concepts and techniques

#### Key Steps/Milestones

- **M1**: Blog Creation

  - [ ] Write 12 blogs supporting SIG & WG efforts

- **M2**: Webinar creation

  - [ ] Create and deliver 2 secure development webinars

- **M3**: Podcast creation

  - [ ] Create a "Secure from the (open) Source" podcast and produce 12 episodes

- **M4**: Promotion using LF network
  - [ ] Contact LF Marketing for podcasting/webinar/blogging resources
  - [ ] Reach out to LF Marketing about opportunities for bootcamps, CTF, speaking

#### Time & resource estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ⛔    |       -       |  8hrs (each)  | Year 1 |
|  **M2**   |   ⛔    |       -       | 40hrs (each)  | Year 1 |
|  **M3**   |   ⛔    |       -       |  4hrs (each)  | Year 1 |
|  **M4**   |   ⛔    |       -       |     20hrs     | Year 1 |

$35K to equip and produce a podcast including graphics and music

- 24 OSSF support hours to facilitate the editing and publication of 12
- 24 OSSF support hours to facilitate the recording, marketing, and publishing of 2 webinars - annual
- 32 OSSF support hours to facilitate podcast marketing and publication

> **CONTRACTOR - TOTAL**: 224 hours

---

## 2.8 Goal: Develop in-person educator-led variations of training materials and deliver bootcamps at conferences

Modify existing materials and develop a training course that could be delivered at conferences including utilizing hands-on labs

### Key Steps/Milestones

- **M1**: Gap analisis existing content

  - [ ] Review existing content
  - [ ] Create new materials for identified gaps or quality improvements

- **M3**: Creation of training slides

  - [ ] Generate modified class-based slide decks for use as a delivery method class training

- **M3**: Creation of training slides for train the trainer
  - [ ] Generate slide decks for training the trainers so they are knowledgeable and skilled to led the in class-based materials

#### Time & resource estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ⛔    |       -       |    120hrs     | Year 1 |
|  **M2**   |   ⛔    |       -       |    3800hrs    | Year 1 |
|  **M3**   |   ⛔    |       -       |    120hrs     | Year 1 |

> **TOTAL**: 24 OSSF and volunteer hours coordinating conference scheduling
> **CONTRACTOR - TOTAL**: 620 hours

---

## 2.9 Goal: Release a RELEASE version for Hack OS for local usage

The SKF Hack OS will also be available for local usage and following the hands-on labs, this will make it easier for educators to consume it in their learning program

### Key Steps/Milestones

- **M1**: Hack OS Lab improvement for local usage

  - [ ] Improve the Hack OS Lab and add preinstalled tools

- **M2**: Build an automated build pipeline for supported programing languages
  - [ ] Build and release Hack OS Lab for Python
  - [ ] Build and release Hack OS Lab for Java
  - [ ] Build and release Hack OS Lab for NodeJS
  - [ ] Build and release Hack OS Lab for Go
  - [ ] Build and release Hack OS Lab for Ruby
  - [ ] Build and release Hack OS Lab for Rust
  - [ ] Build and release Hack OS Lab for C/C++
  - [ ] Build and release Hack OS Lab for DotNet/C#

#### Time & resource estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ✅    |       -       |    220hrs     | Year 1 |
|  **M2**   |   ✅    |       -       |  16hrs(each)  | Year 1 |

> **SKF OPS TEAM - TOTAL**: 348 hours

---

## 2.10 Goal: Staff a partnerships office to develop relationships for content delivery

Hire 2 Partnerships Office staff (one for historically underserved commnunities, one for traditional academia) for outrach and creating meaningfull relationships.

### Key Steps/Milestones

- **M1**: Establish a job description for staff outreach members.

  - [ ] Create a job description for an staff member running and developing partnership office
  - [ ] Get feedback on the job description
  - [ ] post opening and interview candidates
  - [ ] onboard staff members

### Time & resource estimate

| Milestone | SKF Ops | Contractor(s) | Time Estimate |  Year  |
| :-------: | :-----: | :-----------: | :-----------: | :----: |
|  **M1**   |   ✅    |       -       |     10hrs     | Year 1 |

---

---

---

---

---

---

---

---

---

---

---

---

---

---

(Year 2)

## 2.XXX Identify sources of insecure code snippets

### Identify areas where developers are copying or extracting insecure code snippets and work to correct the most widely-applied vulnerable snippets in order to address common problems and challenges, such as those found on StackOverflow. Build on existing research in this area

### Key Steps/Milestones

- [ ] **M1**: Reach out to StackOverflow to see if they have any data on this, open discussions on how to mitigate.
- [ ] **M2**: CodeQL may be a good integration for this - reach out to a team.


