# 🧤 SignTalk AI — Smart Sign-Language Translation Glove

**Bridging the communication gap for the deaf and hard-of-hearing community through wearable AI and sensor fusion.**

[![Project Status](https://img.shields.io/badge/Status-Pre--Prototype%20%26%20System%20Design-blue)]()
[![University Incubation](https://img.shields.io/badge/Incubation-Al%20Ain%20University%20(Under%20Review)-green)]()
[![Validation](https://img.shields.io/badge/User%20Validation-30%2B%20Survey%20Responses-orange)]()

---

## 🎥 Concept & Problem-Solution Demo
Watch our 1-minute overview explaining the communication barriers faced by sign language users, how **SignTalk AI** solves them, and our target beneficiaries:

👉 **[Watch the Concept Video Here](YOUR_YOUTUBE_OR_VIDEO_LINK_HERE)**

---

## 📖 Overview
Millions of people rely on sign language as their primary mode of communication, yet daily interactions in healthcare, education, and public services remain challenging due to the lack of real-time translation tools. 

**SignTalk AI** is an intelligent, wearable glove designed to capture hand gestures, finger flexion, and spatial orientation, translating them instantaneously into audible speech and readable text via a companion interface.

### Key Target Beneficiaries
* **Deaf and hard-of-hearing individuals** seeking seamless, independent daily communication.
* **Healthcare providers & educators** interacting with non-verbal or hearing-impaired patients and students.
* **Customer service & public sector frontlines** aiming for inclusive accessibility.

---

## ⚙️ System Architecture & Future Roadmap
The diagram below outlines the end-to-end hardware-to-software pipeline—from multi-sensor data acquisition to AI gesture classification—along with our phased expansion plan:

![SignTalk AI System Architecture & Roadmap](docs/system_poster.png)

### How It Works (Pipeline)
1. **Gesture Capture:** Embedded flex sensors and an Inertial Measurement Unit (IMU) track finger bending, hand tilt, and motion trajectories.
2. **Signal Processing:** A low-power microcontroller filters raw analog/digital signals in real time.
3. **AI Translation Engine:** Machine learning models classify complex static and dynamic signs across multiple sign languages.
4. **Multimodal Output:** Translated words/sentences are displayed on an integrated wrist module and broadcasted via a built-in speaker/mobile app.

---

## 📊 Market & User Validation
To ensure our solution addresses real-world needs rather than assumptions, we conducted an initial evaluation survey across **30 respondents** (including community members, students, and potential end-users).

* **Key Findings Summary:**
  * **[XX]%** of respondents confirmed that existing translation apps (camera-based) are impractical for on-the-go, real-time conversations.
  * **[XX]%** rated a wearable, hands-free translation glove as **highly useful** in emergency, medical, and educational settings.
  * **[XX]%** highlighted **real-time voice output** and **multi-language support** as their top priority features.

📁 *Raw anonymized survey data is available in [`research/survey_results.csv`](research/survey_results.csv).*

---

## 🏛️ Project Status & Institutional Support
* **Current Phase:** System Architecture, Concept Validation, and Hardware Component Sourcing.
* **University Support:** **SignTalk AI** has been reviewed by the Software & Graduation Projects Committee at **Al Ain University (Abu Dhabi)** and is currently under consideration for institutional adoption and prototype funding to bring the hardware from design to physical testing.

### Development Roadmap
- [x] **Phase 1:** Problem discovery, system architecture design, and concept video production.
- [x] **Phase 2:** Initial user validation survey ($N = 30$) and business feasibility structuring.
- [ ] **Phase 3:** Hardware assembly (Sensors + Microcontroller) and raw data collection *(Up Next)*.
- [ ] **Phase 4:** AI model training, edge deployment, and live field testing.

---

## 📂 Repository Structure
```text
SignTalk-AI/
├── README.md                  # Project overview, validation summary, and roadmap
├── docs/
│   └── system_poster.png      # Visual architecture and future expansion poster
└── research/
    └── survey_results.csv     # Anonymized evaluation dataset (30 responses)
