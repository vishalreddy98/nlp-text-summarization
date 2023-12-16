# wikiHow_text_summarization_llms


### Team:
1. Prashanth Aripirala
2. Rohit Macherla
3. Vishal Reddy Mekala

### Task - Text Summarization
The project aims to utilize pre-trained Large Language Models (LLMs) for text summarization through diverse fine-tuning techniques. Comparative analysis with baseline RNN/LSTM language models is undertaken, utilizing established metrics such as Rouge score and BLEU.

### Dataset:  
A large-scale text summarization dataset (600 MB) was procured from the WikiHow knowledge database. 
Each article in the dataset has a title, a summary which is the concatenation of the headlines of all the paragraphs to serve as the reference summary, and the text which is the concatenation of all the text except the headlines used in the summary variable.

### Dataset Specifications:
The selected wikiHow dataset encompasses approximately 215k data points
For preliminary testing, 10% of the data was utilized for training and 5% for testing. Future scaling considerations will be contingent upon the outcomes of these initial tests.

