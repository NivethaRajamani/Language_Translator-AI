# Language Translator AI

📌 **Project Overview**

The Language Translator AI is a deep learning-based translation system designed to convert text from English to Hindi using the pre-trained Helsinki-NLP *opus-mt-en-hi* transformer model. The project features a **Gradio UI** that allows users to interact with the model for English-to-Hindi translations.

🚀 **Features**

- **English-to-Hindi Translation:** Converts input text from English to Hindi with high accuracy.
- **Pre-trained Transformer Model:** Uses the Helsinki-NLP *opus-mt-en-hi* model.
- **Gradio UI:** A simple interface for translating text without needing to write code.

📂 **Project Structure**

```plaintext
Language_Translator-AI/
│── Eng-Hindi_Translator.ipynb       # Jupyter Notebook for translation
│── requirements.txt                 # Project dependencies
│── README.md                        # Project documentation

```

## 🔧 Installation Instructions

To get started with the project, follow these steps:

### 1. Clone the Repository

Clone the repository to your local machine:
```
git clone https://github.com/NivethaRajamani/Language_Translator-AI.git
cd Language_Translator-AI
```

### 2. Install Required Dependencies
This project requires several Python libraries.

Install them using the following command:

```
pip install -r requirements.txt
```
or 

Alternatively, you can install the libraries manually:

```
pip install transformers torch gradio datasets sacrebleu
```

### 3. Check Python Version

Make sure you're using Python 3.6 or above:

```
python --version
```


### 📝 Running the Translation Notebook

#### 1. Open the Jupyter Notebook
Once the repository is set up and dependencies are installed, launch Jupyter Notebook:

Navigate to Eng-Hindi_Translator.ipynb in the Jupyter Notebook interface.

Open the notebook.

#### 2. Run the Notebook Cells
Execute all the cells in the notebook. The Gradio interface will be launched at the end of the notebook.

#### 3. Using the Gradio Interface
Once the Gradio interface is running, open the link provided in your terminal (e.g., http://127.0.0.1:7860/) in your browser.

* Enter an English sentence in the input field.
* The translation to Hindi will appear in the output field.
![image](https://github.com/user-attachments/assets/c969dace-9281-4794-b499-3daa72ccefc7)

### 📌 Technologies Used

* Python: The primary programming language for the project.
* Hugging Face Transformers: For leveraging pre-trained transformer models.
* Pre-trained Helsinki-NLP Model (opus-mt-en-hi): A neural machine translation model trained for English-to-Hindi translation.
* Gradio: A library to build the interactive web interface.
* TensorFlow (TF): Used for training the translation model.
* PyTorch: Framework used by the Hugging Face model for deep learning.
* Datasets: For loading and processing datasets.

### 📂 Dataset
The model uses the IITB English-Hindi dataset for training and evaluation.

### 🤝 Contributing
Contributions are welcome! If you'd like to improve the project, feel free to fork the repository, create a new branch, and submit a pull request.

📜 License
This project is licensed under the MIT License.

📞 Contact
For any questions or suggestions, feel free to reach out:

* Author: Nivetha Rajamani
* Email: nivetharajamani.jobs@gmail.com
* GitHub: NivethaRajamani
