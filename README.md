# 🔥 FHIR Resource Generator

This repository contains a **FHIR resource generator** that allows the creation of **Patient, Condition, Encounter, and Observation** resources in **Google Colab**.  
The tool provides an interactive interface to **customize fields, choose address realism (Spain) or randomness, and export the generated resources in JSON format**.

---

## 🚀 Features
✅ **Generate FHIR resources**: Patient, Condition, Encounter, and Observation.  
✅ **Realistic Spanish addresses** (or random worldwide addresses).  
✅ **Customizable fields selection** using checkboxes.  
✅ **Automatic JSON export** for integration with FHIR servers.  
✅ **FHIR R5 compliant format**.  

---

## 📂 Files Included 
- **`fhir_generator.ipynb`** → Original Jupyter Notebook for execution in Google Colab.  

---

## 🔧 How to Use
1. Open **Google Colab**: [Google Colab](https://colab.research.google.com/)  
2. Upload `fhir_generator.ipynb`.  
3. Run the notebook and configure:  
   - Select the **FHIR resource type** (Patient, Condition, Observation, or Encounter).  
   - Choose which **fields** to include.  
   - Decide whether to **use realistic addresses in Spain** or **random addresses worldwide**.  
4. Download the generated **FHIR-compliant JSON** for further use.  

---

## 📥 JSON Export
After generating the FHIR resources, the tool allows **automatic downloading** of the JSON file for local use or FHIR server integration.

---

## 📌 Supported FHIR Resources
This generator supports the following **FHIR resources**:

| Resource Type  | Description |
|---------------|------------|
| **Patient**   | Generates patient demographic data, including **realistic or random addresses**. |
| **Condition** | Simulates medical conditions like hypertension, diabetes, asthma, etc. |
| **Encounter** | Creates patient visit records with status (planned, in-progress, finished, etc.). |
| **Observation** | Generates clinical observations (blood pressure, heart rate, temperature). |

---

## 🌎 Contributing & Feedback
If you want to improve this tool, feel free to submit a **Pull Request** or open an **Issue** in this repository.  

🔹 **Repository:** [GitHub Repo Link](https://github.com/22danielblanco/FHIR-Resource-Generator)

---

🎯 **Want any additional features or improvements? Let us know!** 🚀
