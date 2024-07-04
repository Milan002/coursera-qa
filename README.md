# CourseraQuest: Question and Answer System Based on Google Gemini LLM and Langchain for E-learning Platform

This is an end-to-end LLM project based on Google Gemini and Langchain. We are building a Q&A system for the e-learning platform Coursera (website: coursera.org). Coursera offers a wide range of online courses and certifications. They have thousands of learners who use various channels to ask questions. This system will provide a Streamlit-based user interface for students where they can ask questions and get answers.


## Project Highlights

- Uses a real CSV file of FAQs that Coursera is currently using.
- Their human staff will use this file to assist course learners.
- We will build an LLM-based question and answer system that can reduce the workload of their human staff.
- Students should be able to use this system to ask questions directly and get answers within seconds.

## You will learn the following:
  - Langchain + Google Gemini: LLM based Q&A
  - Streamlit: UI
  - Huggingface instructor embeddings: Text embeddings
  - FAISS: Vector database

## Installation

1. Clone this repository to your local machine using:

```bash
git clone https://github.com/Milan002/coursera-qa.git
```

2. Navigate to the project directory:

```bash
cd coursera-qa
```

3. Install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

4. Acquire an API key through the Google Cloud Console and add it to the .env file:

```bash
GOOGLE_API_KEY="your_api_key_here"
```

## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py
```

2. The web app will open in your browser.

- To create a knowledgebase of FAQs, click on the "Create Knowledgebase" button. It will take some time before the knowledgebase is created, so please wait.

- Once the knowledge base is created, you will see a directory called `faiss_index` in your current folder.

- Now you are ready to ask questions. Type your question in the Question box and hit Enter.

## Sample Questions
  - What courses does Coursera offer?
  - How do I enroll in a course?
  - Are there any free courses available?
  - Can I get a certificate after completing a course?
  - How does the peer-grading system work?

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: Contains all the Langchain code.
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.

