# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

### **NAME:** PRESILLA K

### **REGISTER NUMBER:** 212223050038

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.


## **SCENARIO**

You are part of a content development team for an educational technology company that prepares concise learning materials for students.
Your task is to summarize a technical article on **“The Basics of Internet of Things (IoT)”** using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique and platform provides the best summary in terms of:

* **Accuracy** – Correctness of technical details
* **Coherence** – Logical flow and readability
* **Simplicity** – Ease of understanding for undergraduate students
* **Speed** – Response time for generating the summary
* **User Experience** – Ease of prompt creation and AI interaction

---

## **ALGORITHM**

### **Article: The Basics of Internet of Things (IoT)**

The Internet of Things (IoT) refers to a network of interconnected devices that communicate and exchange data using the internet. These devices range from simple sensors to complex systems like smart homes, industrial machinery, and healthcare equipment. The goal of IoT is to collect data, analyze it, and make intelligent decisions to improve efficiency, convenience, and productivity.

IoT works through four key components: sensors, connectivity, data processing, and user interfaces. Sensors collect data such as temperature, motion, or humidity. This data is transmitted over the internet through wireless networks like Wi-Fi, Bluetooth, or cellular connections. Once the data reaches cloud servers, it is analyzed using artificial intelligence or data analytics tools to generate meaningful insights. The results are then displayed through applications, allowing users to monitor and control connected devices in real time.

IoT has many practical applications. In smart homes, IoT allows users to control lights, appliances, and security systems remotely. In healthcare, wearable devices track vital signs like heart rate and oxygen levels, enabling remote patient monitoring. In industry, IoT helps in predictive maintenance, where machines send alerts before failures occur, reducing downtime and costs. In agriculture, IoT sensors monitor soil moisture, temperature, and crop health to optimize irrigation and yield.

However, IoT also faces challenges such as data privacy, cybersecurity risks, and interoperability between different devices and platforms. As IoT continues to expand, ensuring secure communication and ethical data usage remains a top priority.

---

## **EXPERIMENT RESULTS**

### **1. ChatGPT**

#### **Zero-Shot Prompting**

**Prompt:** “Summarize the following article on Internet of Things (IoT) in simple terms for undergraduate students.”

**Output:**
IoT connects smart devices through the internet to share data and automate actions.
It uses sensors, data processing, and apps for monitoring and control.
Applications include smart homes, healthcare, factories, and agriculture.
Challenges include data privacy and security.

---

#### **Few-Shot Prompting**

**Prompt:** Example – “AI helps computers think like humans.”
Now summarize this article on IoT in the same way.

**Output:**
IoT connects devices to the internet so they can collect and share data automatically.
It improves convenience, saves time, and helps in smart homes, hospitals, and industries.
Security and data privacy are key challenges.

---

#### **Chain-of-Thought Prompting**

**Prompt:** “Explain the article step-by-step and then summarize it for undergraduate students.”

**Output:**
IoT = network of connected devices.
Components: sensors → connectivity → data → interface.
Applications: smart homes, healthcare, industry, agriculture.
Challenges: privacy and interoperability.

**Summary:** IoT enables smart connectivity between devices for efficient automation and monitoring but needs strong data security.

---

#### **Role-Based Prompting**

**Prompt:** “You are a professor teaching IoT. Summarize the topic clearly for first-year students.”

**Output:**
IoT means devices talking to each other through the internet.
From smart bulbs to factory sensors, IoT helps automate tasks.
It works through sensors, networks, and cloud computing.
But keeping data secure is vital.

---

### **2. Gemini**

#### **Zero-Shot Prompting**

**Prompt:** “Summarize the following article on IoT in simple terms for undergraduate students.”

**Output:**
IoT links everyday devices via the internet, allowing them to collect, share, and process data.
Used in smart homes, hospitals, and factories.
Challenges: cybersecurity and privacy.

---

#### **Few-Shot Prompting**

**Prompt:** Example – “AI enables smart decision-making.”
Now summarize the article on IoT similarly.

**Output:**
IoT connects physical devices to the internet to share data automatically.
It helps make systems efficient in homes, industries, and healthcare.

---

#### **Chain-of-Thought Prompting**

**Prompt:** “Analyze and summarize step-by-step.”

**Output:**
IoT = connected devices sharing data.
Four components: sensors, network, processing, and interface.
Applications in multiple sectors.
Issues: data protection and compatibility.
**Summary:** IoT improves automation and decision-making but must address privacy and security.

---

#### **Role-Based Prompting**

**Prompt:** “You are a university lecturer. Summarize IoT for your class.”

**Output:**
IoT stands for connecting devices to the internet for smarter living.
Examples: smart thermostats, fitness trackers, industrial robots.
Main concern: data security.

---

### **3. Claude**

#### **Zero-Shot Prompting**

**Prompt:** “Summarize the following article on IoT in simple language.”

**Output:**
IoT is a digital network of connected devices that exchange data through the internet.
It’s used in homes, hospitals, and industries to improve performance and comfort.
Security and compatibility are key issues.

---

#### **Few-Shot Prompting**

**Prompt:** Example – “AI allows computers to learn from experience.”
Now summarize IoT using a similar tone.

**Output:**
IoT connects smart devices to the internet for data sharing and automation.
It improves efficiency in sectors like healthcare and manufacturing.

---

#### **Chain-of-Thought Prompting**

**Prompt:** “Explain IoT step-by-step, then give a short summary.”

**Output:**
IoT → interconnected devices → sensors collect data → networks send it → analysis in the cloud → user controls system.
Applications in homes, hospitals, and farms.
Challenges: data privacy and hacking risks.

**Summary:** IoT enables smart systems that collect and use data intelligently but must stay secure.

---

#### **Role-Based Prompting**

**Prompt:** “You are a professor explaining IoT to beginners. Summarize clearly.”

**Output:**
IoT means connecting physical objects to the internet.
Devices communicate and share data for automation.
Examples: smart homes, medical monitors, and connected vehicles.
Security and privacy remain challenges.

---

## **CONCLUSION**

* **ChatGPT** produced the most **student-friendly summaries** — accurate, concise, and coherent.
* **Gemini** provided technically sound but slightly formal summaries.
* **Claude** gave detailed, logically structured outputs, suitable for advanced readers.


## **RESULT TABLE**

| Platform | Technique        | Accuracy | Coherence | Simplicity | Speed | User Experience | **Total (25)** |
| -------- | ---------------- | -------- | --------- | ---------- | ----- | --------------- | -------------- |
| ChatGPT  | Zero Shot        | 5        | 5         | 5          | 5     | 5               | **25**         |
| ChatGPT  | Few Shot         | 5        | 5         | 5          | 4     | 5               | **24**         |
| ChatGPT  | Chain-of-Thought | 5        | 5         | 4          | 4     | 5               | **23**         |
| Gemini   | Zero Shot        | 5        | 4         | 4          | 5     | 4               | **22**         |
| Gemini   | Role-Based       | 5        | 4         | 4          | 4     | 4               | **21**         |
| Claude   | Zero Shot        | 5        | 5         | 4          | 4     | 4               | **22**         |
| Claude   | Chain-of-Thought | 5        | 5         | 4          | 4     | 5               | **23**         |

---
