# Doctor-Patient-Conversation-Summarizer
# 🩺 Doctor-Patient Conversation Summarizer

## 📌 Project Title

**Doctor-Patient Conversation Summarizer – Text and Speech Analysis Application**

---

## 📖 Description

The **Doctor-Patient Conversation Summarizer** is a Text and Speech Analysis application that converts a recorded doctor-patient conversation into text and generates an organized summary.

The application uses **Speech Recognition** to convert audio into text and then analyzes the text to identify important information such as symptoms, medicines, and doctor's advice.

### 🔄 Application Flow

```text
🎤 Audio Input
      ↓
🗣️ Speech-to-Text
      ↓
📝 Conversation Text
      ↓
🔍 Text Analysis
      ↓
🤒 Symptom Detection
      ↓
💊 Medicine Detection
      ↓
💡 Advice Detection
      ↓
📋 Conversation Summary
```

---

## 🎯 Objectives

* Convert doctor-patient audio into text.
* Analyze the conversation automatically.
* Identify symptoms mentioned by the patient.
* Identify medicines mentioned in the conversation.
* Identify advice or recommendations.
* Generate a simple and organized summary.
* Demonstrate the use of speech and text analysis.

---

## ✨ Features

* 🎤 Upload audio recordings.
* 🗣️ Speech-to-text conversion.
* 🔍 Automatic text analysis.
* 🤒 Symptom detection.
* 💊 Medicine detection.
* 💡 Advice/recommendation detection.
* 📋 Automatic conversation summarization.
* 🌐 Simple Gradio web interface.
* ☁️ Can run in Google Colab.

---

## 🛠️ Technologies Used

| Technology                | Purpose                   |
| ------------------------- | ------------------------- |
| Python                    | Main programming language |
| Google Colab              | Development and execution |
| Gradio                    | Web application interface |
| SpeechRecognition         | Speech-to-text conversion |
| PyDub                     | Audio conversion          |
| Regular Expressions       | Text processing           |
| Google Speech Recognition | Speech recognition        |

---

## 📥 Input

The application accepts a recorded doctor-patient conversation in audio format.

### Example Conversation

```text
Doctor: What problem are you having?

Patient: I have been having a headache for three days.

Doctor: Do you have a fever?

Patient: No, but I feel tired.

Doctor: Are you taking any medicines?

Patient: No.

Doctor: Get enough rest and drink plenty of water.
```

---
<img width="939" height="468" alt="Screenshot 2026-10-04 144635" src="https://github.com/user-attachments/assets/983d52ed-df53-45f6-9662-afc68d18fbbb" />
<img width="922" height="215" alt="Screenshot 2026-10-04 144855" src="https://github.com/user-attachments/assets/450baa40-1025-4977-9fa0-ee9252c7186b" />

<img width="920" height="336" alt="Screenshot 2026-10-04 144942" src="https://github.com/user-attachments/assets/d69326e1-e7d0-48fc-b10a-e5cc12dbdc70" />


## 📤 Output

### 🗣️ Converted Conversation

```text
I have been having a headache for three days.
No, but I feel tired.
I am not taking any medicine.
Get enough rest and drink plenty of water.


