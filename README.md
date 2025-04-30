# Co-Reviewer: Can AI Review Like a Human? An Agentic Framework for LLM–Human Alignment in Peer Review

## 📝 Overview
Co-Reviewer is an AI-powered system that automates research paper reviews by analyzing PDFs and generating structured feedback.

## 🚀 Features
- AI-based research paper analysis
- Automated structured review generation
- Supports multiple research papers

![image](https://github.com/user-attachments/assets/52140527-e54f-402d-bc2e-3a8ae9d22b20)

## 📌 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/co-reviewer.git
cd co-reviewer
```

### 2️⃣ Install Dependencies
Ensure Python 3.8+ is installed, then run:
```bash
pip install crewai pymupdf openai
```

### 3️⃣ Prepare Input PDFs
Place research papers in the `ICLR_2020_papers/` directory.

### 4️⃣ Run the Review System
```bash
jupyter notebook co-reviewer-agent.ipynb
```

### 📤 Output Format
Each paper receives a structured review saved as:
```
📄 ICLR_2020_LLM_reviews/paper_title_review.txt
```

#### Example Review Format
```yaml
Paper Title: Example Research Paper
Summary: This paper explores...
Strengths:  
  - Strong methodology  
  - Clear problem definition
Weaknesses:  
  - Lacks empirical evaluation
Overall Rating: 7/10
```

## **Contact**  

For queries, reach out to:  
- **Prabhat Kumar Bharti**: [dept.csprabhat@gmail.com](mailto:dept.csprabhat@gmail.com)  
- **Mihir Panchal**: [mihirpanchal5400@gmail.com](mailto:mihirpanchal5400@gmail.com)  
- **Viral Dalal**: [viraldalal04@gmail.com](mailto:viraldalal04@gmail.com)  

---

## **License**  

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.  

---
