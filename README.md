# Wikipedia Question Answering System
This is a project for a Wikipedia Question Answering system, which uses a pre-trained transformer model for question-answering and HTML parsing to retrieve the context. The system can answer a wide range of questions based on the information available on Wikipedia.


## Installation
1. To use this system, first clone this repository to your local machine using the following command:

```
git clone https://github.com/daparasyte/Wikipedia_QnA.git
```
2. Next, navigate to the project directory 
```
cd Wikipedia_QnA
```

3. Install the necessary dependencies using pip:
```
pip install -r requirements.txt
```

## Usage
The Wikipedia Question Answering system can be run using the `app.py` script. You can run the script using the following command:
```
streamlit run app.py
```

The system will use the RoBERTa model and HTML parsing to retrieve the most relevant information from Wikipedia and provide an answer to your question. You just need to provide the Wikipedia article link and the question you want to ask to the model. 

![image](https://user-images.githubusercontent.com/62950304/235082927-63fc4409-e4b7-44d7-a879-e2da4c4fa305.png)
