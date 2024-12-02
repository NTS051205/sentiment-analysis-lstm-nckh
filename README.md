# Sentiment Analysis with LSTM for NEU Learners  

This project focuses on **Sentiment Analysis**, an essential task in the field of Natural Language Processing (NLP). By leveraging this technique, schools, such as NEU (National Economics University), can better understand learners' attitudes and emotions based on feedback. For this project, we implemented a Long Short-Term Memory (LSTM) neural network model to analyze learner sentiment using the IMDb movie review dataset.

## **Project Goals**  
1. Train an LSTM model to classify sentiment (positive or negative) from text data.  
2. Evaluate the model's performance on the IMDb dataset.  
3. Apply the trained model to classify sentiment in an input dataset (Excel or CSV format).  
4. Output the sentiment classification results into a new column in the original input file.

## **Key Concepts**  

### **LSTM (Long Short-Term Memory)**  
LSTM is a variant of Recurrent Neural Networks (RNN) designed to effectively process and retain information over long sequences. It is particularly well-suited for sequential data, such as text or audio, thanks to its gate mechanism that determines which information to retain or forget.  

### **Sentiment Analysis**  
Sentiment Analysis involves classifying text into categories, typically positive or negative, based on the emotions expressed in the content. This helps in extracting valuable insights from textual data.

## **Project Workflow**  
1. **Training the Model**:  
   - Use the IMDb Reviews dataset to train the LSTM model.  
   - Evaluate the model's accuracy against the original dataset.  

2. **Processing Input Files**:  
   - Accept input files in Excel (.xlsx) or CSV (.csv) formats.  
   - Perform preprocessing to ensure the data is ready for analysis.  

3. **Generating Output**:  
   - Analyze the sentiment of each text entry in the input file.  
   - Append a new column labeled "Sentiment" to the file with the classification results.  

4. **Result Export**:  
   - Save the updated file with the sentiment column back into Excel or CSV format.  

## **Installation and Usage**  

### **1. Prerequisites**  
- Python (>=3.7)  
- Required libraries: TensorFlow, Pandas, Numpy, etc.  

### **2. Steps to Run**  
1. Clone this repository:  
   * Prerequisites: [Python 3.9](https://www.python.org/downloads/) (ensure Python is added to [PATH](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013)) + [Git](https://www.markdownguide.org/basic-syntax/) Client 
   * Open GIT CMD >> navigate to working directory >> Clone this Github Repo (or download project files from GitHub directly)
      git clone (https://github.com/NTS051205/sentiment-analysis-lstm-nckh)
   

