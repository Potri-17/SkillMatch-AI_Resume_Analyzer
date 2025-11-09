<h1> AI Resume Analyzer</h1

Introduction

Developed an advanced AI application that utilizes LLM and OpenAI for comprehensive resume analysis. It excels at summarizing the resume, evaluating strengths, identifying weaknesses, and offering personalized improvement suggestions, while also recommending the perfect job titles. Additionally, it seamlessly employs Selenium to extract vital LinkedIn data, encompassing company names, job titles, locations, job URLs, and detailed job descriptions. This application simplifies the job-seeking journey by equipping users with comprehensive insights to elevate their career opportunities.


Table of Contents

Key Technologies and Skills
Installation
Usage
Features
Contributing
License
Contact

Key Technologies and Skills

Python
NumPy
Pandas
LangChain
LLM
OpenAI
Selenium
Streamlit
Hugging Face
AWS

Installation

To run this project, you need to install the following packages:

pip install numpy
pip install pandas
pip install streamlit
pip install streamlit_option_menu
pip install streamlit_extras
pip install PyPDF2
pip install langchain
pip install openai
pip install tiktoken
pip install faiss-cpu
pip install selenium

Usage

To use this project, follow these steps:

Clone the repository: https://github.com/SubashSK777/AI_Resume_Analyzer.git
Install the required packages: pip install -r requirements.txt
Run the Streamlit app: streamlit run app.py
Access the app in your browser at http://localhost:8501

Features

Easy User Experience:

Resume Analyzer AI makes it easy for users. You can upload your resume and enter your OpenAI API key without any hassle. The application is designed to be user-friendly so that anyone can use its powerful resume analysis features.
It also uses the PyPDF2 library to quickly extract text from your uploaded resume, which is the first step in doing a thorough analysis.
Smart Text Analysis with Langchain:

What makes it special is how it analyzes text. It uses a smart method called the Langchain library to break long sections of text from resumes into smaller chunks, making them more meaningful.
This clever technique improves the accuracy of the resume analysis, and it gives users practical advice on how to enhance their job prospects.
Enhanced OpenAI Integration with FAISS:

Seamlessly connecting to OpenAI services, the application establishes a secure connection using your OpenAI API key. This integration forms the basis for robust interactions, facilitating advanced analysis and efficient information retrieval.
It uses the FAISS(Facebook AI Similarity Search) library to convert both the text chunks and query text data into numerical vectors, simplifying the analysis process and enabling the retrieval of pertinent information.
Intelligent Chunk Selection and LLM:

Utilizing similarity search, Resume Analyzer AI compares the query and chunks, enabling the selection of the top 'K' most similar chunks based on their similarity scores.
Simultaneously, the application creates an OpenAI object, particularly an LLM (Large Language Model), using the ChatGPT 3.5 Turbo model and your OpenAI API key.
Robust Question-Answering Pipeline:

This integration establishes a robust question-answering (QA) pipeline, making use of the load_qa_chain function, which encompasses multiple components, including the language model.
The QA chain efficiently handles lists of input documents (docs) and a list of questions (chunks), with the response variable capturing the results, such as answers to the questions derived from the content within the input documents.
Comprehensive Resume Analysis:

Summary: Resume Analyzer AI provides a quick, comprehensive overview of resumes, emphasizing qualifications, key experience, skills, projects, and achievements. Users can swiftly grasp profiles, enhancing review efficiency and insight.
Strength: Effortlessly conducting a comprehensive resume review, it analyzes qualifications, experience, and accomplishments. It subsequently highlights strengths, providing job seekers with a competitive edge.
Weakness: AI conducts thorough analysis to pinpoint weaknesses and offers tailored solutions for transforming them into strengths, empowering job seekers.
Suggestion: AI provides personalized job title recommendations that align closely with the user's qualifications and resume content, facilitating an optimized job search experience.

🚀 Streamlit application: https://huggingface.co/spaces/Potriselvan17/AI_Resume_Analyzer


Selenium-Powered LinkedIn Data Scraping:

Utilizing Selenium and a Webdriver automated test tool, this feature enables users to input job titles, automating the data scraping process from LinkedIn. The scraped data includes crucial details such as company names, job titles, locations, URLs, and comprehensive job descriptions.
This streamlined process enables users to easily review scraped job details and apply for positions, simplifying their job search and application experience.

Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.


License

This project is licensed under the MIT License. Please review the LICENSE file for more details.


Contact

📧 Email: potriselvan19@gmail.com

🌐 LinkedIn: linkedin.com/in/Potriselvan17

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.
