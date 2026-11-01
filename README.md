# ⚙️ Deadlock Lab – AI-Assisted Dashboard Development and Deadlock Analysis

An interactive web-based dashboard developed using **Python and Streamlit** for understanding Operating System deadlocks, resource allocation, deadlock avoidance, detection, prevention and recovery.

## 📌 Project Information

- **Subject:** Operating Systems
- **Activity:** IA Assignment – Activity 2
- **Project Title:** Deadlock Lab
- **Technology:** Python
- **Framework:** Streamlit
- **Domain:** Operating Systems

## 🎯 Project Objectives

1. Understand the concept and necessary conditions of deadlocks.
2. Implement Banker's Algorithm for deadlock avoidance.
3. Analyze safe and unsafe system states.
4. Demonstrate resource allocation and resource requests.
5. Implement deadlock detection and recovery.
6. Understand different deadlock prevention techniques.
7. Test boundary conditions and invalid inputs through an interactive dashboard.

## 🚀 Features

### 1. Deadlock Concepts
- Introduction to deadlocks.
- Necessary conditions for deadlock.
- Resource Allocation Graph.
- Deadlock handling strategies.

### 2. Deadlock Prevention
- Elimination of necessary deadlock conditions.
- Resource ordering.
- Prevention of circular wait and hold-and-wait.

### 3. Deadlock Avoidance – Banker's Algorithm
- Allocation Matrix.
- Maximum Matrix.
- Available Resources.
- Automatic Need Matrix calculation.
- Work vector updates.
- Safe sequence identification.
- Safe and unsafe state analysis.

### 4. Deadlock Detection and Recovery
- Resource allocation analysis.
- Identification of deadlocked processes.
- Circular wait demonstration.
- Process termination and resource release.

### 5. Deadlock Ignorance
- Explanation of the Ostrich Algorithm.
- Understanding when deadlocks may be ignored.

### 6. Interactive Deadlock Games
- Practice activities.
- Concept-based learning.
- Interactive demonstrations.

### 7. Test Lab
The dashboard includes six analytical test scenarios:

| Test Case | Description |
|---|---|
| TC1 | Safe State |
| TC2 | Resource Request Exceeds Available Resources |
| TC3 | Resource Request Produces an Unsafe State |
| TC4 | Deadlock Detection |
| TC5 | Deadlock Prevention |
| TC6 | Boundary and Invalid Inputs |

## 🛠️ Technologies Used

- Python
- Streamlit
- NumPy
- Pandas
- GitHub
- Streamlit Community Cloud

## 📂 Project Structure

```text
OS_IA_Activity/
│
├── streamlit_app.py
├── requirements.txt
├── README.md
│
├── core/
│   ├── project.py
│   ├── ui.py
│   └── algorithm modules
│
├── app_pages/
│   ├── home.py
│   ├── concepts.py
│   ├── prevention.py
│   ├── avoidance.py
│   ├── detection.py
│   ├── ignorance.py
│   ├── games.py
│   ├── test_lab.py
│   ├── ai_usage.py
│   └── resources.py
│
├── tests/
│
├── .streamlit/
│
└── class_notes/
```

*Note: The structure above is illustrative. Update it to match the actual files in your repository.*

## 💻 Installation and Execution

### Step 1: Clone the repository

```bash
git clone https://github.com/Samu7709/OS_IA_Activity.git
```

### Step 2: Navigate to the project directory

```bash
cd OS_IA_Activity
```

### Step 3: Install dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the application

```bash
streamlit run streamlit_app.py
```

The dashboard will open in your default web browser.

## 🧪 Testing

The dashboard is intended to demonstrate:

- Safe and unsafe system states.
- Valid resource requests.
- Waiting and deferred resource requests.
- Unsafe resource request rejection.
- Deadlock detection.
- Deadlock prevention and recovery.
- Boundary and invalid input validation.

Actual test results should be recorded after executing the scenarios.

## ☁️ Deployment

The application can be deployed using Streamlit Community Cloud.

1. Upload the project source code to GitHub.
2. Connect the GitHub repository to Streamlit Community Cloud.
3. Select `streamlit_app.py` as the main application file.
4. Deploy the application.

## 👥 Team Information

- **Institute:** MIT AOE Alandi
- **Division:** A

### Group Members

1. 202401040131 – Samarth Kadam
2. 202401040054 – Hrishikesh Koshti
3. 202401040270 – Devansh Agrawal
4. 202401040239 – Dhruvesh Biraris

## 🤖 AI Usage

AI-assisted tools may be used for:
- Understanding Operating System concepts.
- Algorithm development and explanation.
- Debugging and code review.
- Generating test cases.
- Documentation assistance.

All AI-generated code and outputs must be reviewed, tested and verified by the project team. Refer to the AI Usage Record for the actual tools and prompts used.

## 📚 Acknowledgement

We acknowledge the use of reference materials and authorized project examples during the learning and development process. The project team is responsible for reviewing, modifying, testing and understanding the submitted implementation.

---

**Operating Systems – IA Activity 2**

*Deadlock Analysis and Resource Allocation Dashboard*
