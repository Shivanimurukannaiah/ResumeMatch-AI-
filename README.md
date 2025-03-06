# ResumeMatch AI  
*A Smart Applicant Tracking System for Resume Optimization*

---

## 🎯 Project Overview  
ResumeMatch AI is an intelligent Applicant Tracking System (ATS) designed to streamline the resume evaluation process. Using advanced **Google Generative AI** models, it analyzes resumes against job descriptions to provide actionable feedback. Built with a focus on the tech industry, including software engineering, data science, and big data engineering, the system helps users enhance their resumes for better visibility in a competitive job market.

**Key Features:**  
- Upload resumes in PDF format for analysis.  
- Extract relevant information using `PyPDF2`.  
- Generate a percentage match with the job description.  
- Identify missing keywords and provide a refined profile summary.  
- User-friendly interface powered by **Streamlit**.

---

## 📂 Files & Setup  

### **Prerequisites**  
- Python 3.x installed on your system.  
- Libraries: `streamlit`, `PyPDF2`, `google-generativeai`, `python-dotenv`.  
- API Key from Google Gemini Large Language Model.

### **File Structure**  
ResumeMatch-AI/
├── app.py # Main application file
├── requirements.txt # Python dependencies
├── .env # API key configuration file
├── README.md # Project documentation
└── LICENSE # License information


---

## 🚀 Getting Started  

### Installation Steps  

#### **Option 1: Installation from GitHub**  

1. **Clone the Repository:**  
   Open your terminal and run:  
git clone https://github.com/YourUsername/ResumeMatch-AI.git
cd ResumeMatch-AI


2. **Create a Virtual Environment (Optional):**  
conda create -p <Environment_Name> python==<python_version> -y
conda activate <Environment_Name>

3. **Install Dependencies:**  
pip install -r requirements.txt

4. **Set Up API Key:**  
- Create a `.env` file in the project root directory.  
- Add your API key as follows:  
  ```
  GOOGLE_API_KE Y=your_api_key_here
  ```

5. **Run the Application:**  
streamlit run app.py

6. **Access the Application:**  
Open your browser at the URL provided by Streamlit (e.g., `http://localhost:8501`).

---

## 🛠️ Built With  

- **Streamlit**: For creating an interactive web application.  
- **PyPDF2**: For extracting data from PDF files.  
- **Google Generative AI**: For advanced resume analysis and feedback generation.  

---

## 🤝 Contributing  

We welcome contributions to make ResumeMatch AI even better! Here’s how you can contribute:  

1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m "Add feature"`).  
4. Push to the branch (`git push origin feature-name`).  
5. Open a pull request.

---

## 📜 License  

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

---

## 📧 Contact  

For questions or feedback, reach out to:  
Hema Kalyan Murapaka - kalyanmurapaka274@gmail.com

---
