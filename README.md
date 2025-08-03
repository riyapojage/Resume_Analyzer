# Resume Screening Application

A machine learning application that automatically categorizes resumes into different job categories based on their content.

## Project Overview

This Resume Screening App uses Natural Language Processing (NLP) and Machine Learning to automatically classify resumes into 25 different professional categories such as "Data Science", "Java Developer", "Network Security Engineer", etc. The application analyzes the text content of uploaded resumes and predicts the most suitable job category for each candidate, helping recruiters and HR professionals streamline their resume screening process.

## Features

- **Resume Upload**: Support for multiple file formats (PDF, DOCX, TXT)
- **Text Extraction**: Automatically extracts text from uploaded documents
- **Text Preprocessing**: Cleans and normalizes resume content by removing URLs, special characters, etc.
- **Classification**: Uses Support Vector Machine (SVM) model with TF-IDF vectorization for accurate categorization
- **User-friendly Interface**: Built with Streamlit for easy interaction and visualization
- **Multi-class Classification**: Supports 25 different job categories

## Supported Job Categories

- Data Science
- HR
- Advocate
- Arts
- Web Designing
- Mechanical Engineer
- Sales
- Health and fitness
- Civil Engineer
- Java Developer
- Business Analyst
- SAP Developer
- Automation Testing
- Electrical Engineering
- Operations Manager
- Python Developer
- DevOps Engineer
- Network Security Engineer
- PMO
- Database
- Hadoop
- ETL Developer
- DotNet Developer
- Blockchain
- Testing

## Technical Stack

- **Python**: Core programming language
- **Streamlit**: Web application framework
- **scikit-learn**: Machine learning library for model training and prediction
- **PyPDF2**: PDF text extraction
- **python-docx**: DOCX text extraction
- **pandas & numpy**: Data manipulation and analysis
- **TF-IDF Vectorization**: Feature extraction technique for text data
- **Support Vector Machine**: Classification algorithm (achieved 100% accuracy on test dataset)

## How It Works

1. **Data Preparation**: The model was trained on a dataset of resumes from various professional categories
2. **Text Preprocessing**: Resume text is cleaned to remove noise (URLs, special characters, etc.)
3. **Feature Extraction**: TF-IDF vectorization converts text to numerical features
4. **Model Training**: SVM classifier was trained and achieved perfect accuracy on test data
5. **Prediction**: New resumes are processed through the same pipeline to predict job categories

## Installation and Setup

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/Resume-Screening-App.git
   cd Resume-Screening-App
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

4. Access the application in your browser at `http://localhost:8501`

## Usage

1. Open the application in your web browser
2. Upload a resume in PDF, DOCX, or TXT format
3. The application will process the resume and display the predicted job category
4. You can optionally view the extracted text content

## Model Performance

The Support Vector Machine model used for classification achieved 100% accuracy on the test dataset, outperforming other algorithms like K-Nearest Neighbors (99.29% accuracy) and Random Forest.

## Future Improvements

- Add confidence scores for predictions
- Support for more file formats
- Enhanced text extraction capabilities
- Multi-label classification for versatile candidates
- Deployment options (cloud, container, etc.)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Resume dataset used for training the model
- Contributors and maintainers of the libraries used in this project