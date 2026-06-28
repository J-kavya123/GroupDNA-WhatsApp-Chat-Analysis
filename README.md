# 📊 GroupDNA – WhatsApp Chat Analysis

## 📖 Project Overview

GroupDNA is a Python-based WhatsApp chat analysis project developed as part of my Python Internship. The project analyzes exported WhatsApp group chats and generates meaningful insights about group communication, participant activity, response patterns, and personality archetypes.

The project uses Python, NumPy, and the datetime module to process chat data and produce a structured analytics report.

---

## 🎯 Features

### ✅ Feature 1 – Chat Parser
- Reads WhatsApp exported chat file
- Extracts timestamp, sender, and message
- Ignores system messages
- Ignores deleted messages
- Ignores media omitted messages

### ✅ Feature 2 – Group Overview
- Total messages
- Total participants
- Chat duration
- Messages per participant
- Average message length

### ✅ Feature 3 – Activity Analysis
- Busiest day
- Busiest hour
- Most active participant

### ✅ Feature 4 – Activity Heatmap (NumPy)
- Creates a participant × hour activity matrix
- Displays participant activity across 24 hours
- Detects night activity

### ✅ Feature 5 – Top Words Analysis
- Converts words to lowercase
- Removes punctuation
- Removes stop words
- Finds the Top 10 most frequently used words
- Displays word frequency using bar charts

### ✅ Feature 6 – Response Pattern Analysis
- Calculates average response time
- Finds fastest and slowest responders
- Calculates silent days for participants

### ✅ Feature 7 – Personality Archetype Detection
Assigns personality archetypes such as:
- The Spammer
- The Night Owl
- The Storyteller
- The Ghost
- The Active Member

### ✅ Feature 8 – Final Report
Generates a clean summary report containing all analytics.

---

## 🛠 Technologies Used

- Python
- NumPy
- datetime
- Jupyter Notebook

---

## 📂 Project Structure

```
GroupDNA-WhatsApp-Chat-Analysis/
│
├── GroupDNA.ipynb
├── README.md
├── requirements.txt
├── sample_chat.txt
└── screenshots/
```

---

## ▶️ How to Run

1. Clone this repository.

```
git clone <repository-link>
```

2. Install the required library.

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```
jupyter notebook
```

4. Run all the cells in `GroupDNA.ipynb`.

---

## 📈 Sample Output

The project generates insights such as:

- Total Messages
- Chat Duration
- Most Active Participant
- Busiest Day
- Busiest Hour
- Activity Heatmap
- Top Words
- Response Patterns
- Personality Archetypes
- Final Summary Report

---

## 📸 Screenshots

Add screenshots of your project outputs inside the `screenshots` folder and display them here.

Example:

- Final Report
- Activity Heatmap
- Top Words
- Personality Archetypes

---

## 👩‍💻 Author

**Jalagadu Kavya**

Python Internship Project

---

## 📌 Note

This project is created for educational purposes as part of a Python internship.

Personal WhatsApp chat data has been excluded to protect user privacy.