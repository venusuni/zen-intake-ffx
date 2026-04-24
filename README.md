# 🏛️ ZenIntake (c0mpiled-10/DC Hackathon)
**Track:** Intake & Applications (Tom Blomfield RFS)

ZenIntake brings calm, speed, and security to government benefit applications. Built for the Fairfax County Neighborhood and Community Services (NCS), this AI-driven portal transforms unstructured application documents into verified "Golden Records."

### 🚀 The Problem & Solution
Caseworkers spend weeks manually reviewing benefit applications and verifying employers, leaving the system vulnerable to fake paystubs and duplicate profiles. ZenIntake solves this by:
1. **Automated Extraction:** Instantly pulling applicant data from uploaded documents.
2. **Master Client Index (MCI) Matching:** Using probabilistic matching to link new applications to existing resident "Golden Records" to prevent double-dipping.
3. **Real-Time Fraud Prevention:** Integrating the **Crustdata API** to instantly verify the applicant's declared employer, ensuring funds only go to legitimately employed residents.

### 💻 Tech Stack
* **Front-End:** Python, Streamlit
* **AI & Logic:** Fuzzy string matching (`thefuzz`), simulated Azure OpenAI extraction
* **Verification API:** Crustdata Firmographic Data

### 🔗 Submission Links
* **Live Demo / Loom Video:** [Insert Link Here]
* **Pitch Deck:** [Insert Link Here]

### 🛠️ How to Run Locally
```bash
pip install streamlit thefuzz pandas
streamlit run app.py
