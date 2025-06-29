# TrialMatchAI

An AI-powered assistant to automate clinical trial eligibility checks, built for the IBM AI & Automation Unpacked Hackathon.

---

## 💡 Problem Statement

Clinical research teams spend hours manually reviewing patient data to check eligibility for clinical trials. This slows down trial enrollment, increases costs, and risks errors. Existing tools often rely on keyword matches, but trial criteria and patient histories are expressed in complex, narrative language that’s hard to automate.

---

## ✅ Solution

TrialMatch AI uses IBM Granite models to:
- Read trial eligibility criteria (free text)
- Read a patient medical summary (free text)
- Decide whether the patient is Eligible or Not Eligible
- Provide a brief explanation for the decision

This significantly speeds up screening and reduces errors in clinical research workflows.

---

## 🎯 Target Users

- Clinical Research Coordinators
- Principal Investigators
- Healthcare Institutions running trials
- Health Informatics teams exploring AI automation

---

## 🔍 How It Works

[Trial Criteria Text] + [Patient Data]
↓
IBM Granite Model
↓
[Eligibility Decision + Explanation]


- Built and tested using IBM watsonx.ai Prompt Lab
- Uses Granite-3-3-8b-instruct model for reasoning tasks

---

## 🧪 Example Prompt

**Trial Criteria:**
- Age between 40 and 65 years inclusive
- BMI less than 30
- No history of cancer
- No uncontrolled chronic illnesses

**Patient Summary:**
> The patient is 58 years old, BMI is 28.5, has well-managed diabetes, and no cancer history.

**Expected Output:**
> Eligible. With the updated information, the patient meets all eligibility criteria: age (58 within 40-65), BMI (28.5 under 30), no cancer history, and well-managed diabetes (not considered uncontrolled).

---

## 🎥 Demo Video

Watch the demo here:  
[https://youtu.be/RfPfE7RVGnU](https://youtu.be/RfPfE7RVGnU)

---

## 📂 Repository Contents

- `README.md` → This file
- `prompts/` → Example prompt templates
- `images/` → Screenshots of the workflow and outputs

---

## 🏆 Hackathon

Built for:  
**IBM AI & Automation Unpacked Hackathon, June 2025**
