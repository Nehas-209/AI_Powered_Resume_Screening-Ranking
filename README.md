📄 AI Resume Screening & Candidate Ranking System

🚀 Project Overview
The AI Resume Screening & Candidate Ranking System automates the process of evaluating and ranking resumes based on a given job description. The system uses AI techniques to analyze resumes by extracting text, converting it to numerical vectors, and calculating similarity scores. The ranked results are displayed to the user, saving time and ensuring a more efficient and objective resume screening process.

🎯 Key Features
Job Description Input: Upload the job description to define the criteria for evaluating resumes.

PDF Upload Module: Upload multiple PDF resumes for analysis.

Text Extraction: Extracts text from resumes using PyPDF2 for further processing.

Vectorization: Converts the extracted text and job description into numerical vectors using TfidfVectorizer.

Similarity Calculation: Calculates cosine similarity between the job description and resumes to measure relevance.

Resume Ranking: Ranks resumes based on similarity scores.

Results Display: Presents the ranked resumes in descending order of relevance.

⚡️ System Workflow
Input Module:

 Uploads the job description and multiple resumes in PDF format.

Text Extraction Module:

 Extracts text from resumes using PyPDF2.

Ranking Module:

 Converts text to numerical vectors using TfidfVectorizer.

 Calculates cosine similarity to evaluate relevance.

 Ranks resume based on similarity scores.

Output Module:

 Displays the ranked resumes in a clear and concise format.
 🛠️ Tech Stack
Backend: Python

Libraries/Packages:

Streamlit - For creating the web application.

PyPDF2 - For extracting text from PDF resumes.

scikit-learn - For vectorization and similarity calculation.

Pandas - For managing and displaying ranked results.

📚 Prerequisites
Make sure you have the following installed:

Python 3.8 or higher

pip (Python package manager)

📦 Installation
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/AI-Resume-Ranking-System.git
2. Navigate to the project directory
bash
Copy
Edit
cd AI-Resume-Ranking-System
3. Create a virtual environment
bash
Copy
Edit
python -m venv venv
4. Activate the virtual environment
Windows:

bash
Copy
Edit
venv\Scripts\activate
Linux/Mac:

bash
Copy
Edit
source venv/bin/activate
5. Install dependencies
bash
Copy
Edit
pip install -r Requirements.txt

▶️ Usage
1. Run the application
bash
Copy
Edit
streamlit run resume_ranking.py
2. Open the browser and navigate to:
arduino
Copy
Edit
http://localhost:8501
3. Upload job description and resumes
Enter the Job Description.

Upload multiple PDF Resumes.

Click on Process to rank the resumes.

📊 Output
Displays ranked resumes in descending order of relevance.

Provides a detailed score to help with decision-making.

🎁 Contributing
Contributions are welcome! Feel free to submit issues and pull requests to enhance the system.


