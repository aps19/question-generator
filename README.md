# question-generator
This app generates question from the input text. 

High-level outline of this project:

1. **Data Collection and Preprocessing:**
   - Gather a dataset.
   - Preprocess the text data by tokenizing, removing stop words, and performing other text cleaning tasks.

2. **Text Summarization (Optional):**
   - Implement text summarization techniques to create concise summaries of the input text. 
   - These summaries can serve as a basis for generating questions.

3. **Question Generation:**
   - Use NLP techniques to generate questions. This can be divided into two categories:
     - **MCQ Generation:** For MCQs, you can use methods like Named Entity Recognition (NER) to identify entities in the text and formulate questions based on them. Use algorithms to create distractors (wrong answer choices).
     - **Subjective Question Generation:** For subjective questions, you might need to extract key information from the text and formulate open-ended questions.

4. **Answer Generation (for Subjective Questions):**
   - If you're generating subjective questions, you'll also need to generate model answers. 
   - Use extractive or abstractive summarization techniques for this purpose.

5. **User Interface (UI):**
   - Create a user-friendly interface for users to input text and receive generated questions.
   - This can be a web app [streamlit, flask, fastAPI] etc.

6. **Machine Learning Models:**
   - Implement machine learning or deep learning models for various NLP tasks, such as named entity recognition, question generation, and answer generation. 

7. **Evaluation:**
   - Develop an evaluation metric to assess the quality of the generated questions.

8. **Iterate and Improve:**
   - Based on the evaluation results, iterate on your models and algorithms to improve the quality of generated questions.

9. **Deployment:**
   - Deploy your NLP app to make it accessible to users. Hugging-face.


