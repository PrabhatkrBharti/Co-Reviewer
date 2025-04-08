# Agentic AI Reviewer

## 📝 Overview
Agentic AI Reviewer is an AI-powered system that automates research paper reviews by analyzing PDFs and generating structured feedback.

## 🚀 Features
- AI-based research paper analysis
- Automated structured review generation
- Supports multiple research papers

## 📌 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/agentic-ai-reviewer.git
cd agentic-ai-reviewer
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
python review_pipeline.py
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

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

## 📧 Contact
For inquiries, reach out via email or open an issue on GitHub.
