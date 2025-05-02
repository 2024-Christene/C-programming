# Hospital Management System (C Project)

## 📋 Description

This is a simple **Hospital Management System** written in **C** that allows users to manage basic hospital operations for different roles: **Doctor**, **Nurse**, and **Pharmacist**.

It supports:
- Adding patient records.
- Viewing patient details (Doctor).
- Entering patient vitals (Nurse).
- Viewing disease-based medicine suggestions (Pharmacist).

---

## 🛠 Features

- Add and store patient details (ID, Name, Age, Disease).
- Doctor panel to view all patient data.
- Nurse panel to record basic vitals.
- Pharmacist panel to view disease and suggested medicine.

---

## 👨‍💻 Roles Supported

### 1. Doctor
- Logs in with Name, ID, and Department.
- Can view all patients with their details.

### 2. Nurse
- Inputs patient ID to check existence.
- Enters basic vitals: awake, breathing, food intake.

### 3. Pharmacist
- Enters patient ID.
- Gets disease-based prescription:
  - **Fever** → Paracetamol
  - **Cold** → Cetrizine
  - **Cough** → Ascoril LS
  - Others → "Consult Doctor"

---

## ✅ How to Run

1. Make sure you have a C compiler (like GCC).
2. Save the code as `hospital.c`.
3. Compile and run:
   ```bash
   gcc hospital.c -o hospital
   ./hospital
