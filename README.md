# GPT-2 Text Generation Web Application

An interactive web application for generating human-like text using a **pre-trained GPT-2 Transformer model**.  
This project demonstrates the practical application of modern **Natural Language Processing (NLP)** techniques without training a model from scratch.

---

## 🚀 Project Overview
The GPT-2 Text Generation Web Application enables users to provide a text prompt and generate coherent text through a clean and intuitive web interface.  
The application leverages **transfer learning** by using a pre-trained language model, making advanced NLP accessible and efficient.

---

## Key Features
- Pre-trained GPT-2 language model from Hugging Face  
- Interactive and responsive web UI built with Gradio  
- Customizable text generation parameters:
  - **Max New Tokens** – controls output length  
  - **Temperature** – controls creativity and randomness  
- Automatic detection of CPU or GPU runtime  
- Shareable public web interface  

---

## Tech Stack
- **Programming Language:** Python  
- **Deep Learning Framework:** PyTorch  
- **NLP Library:** Hugging Face Transformers  
- **Web Interface:** Gradio  
- **Development Environment:** Google Colab  

---

## System Architecture
1. User inputs a text prompt through the web interface  
2. Text is tokenized using the GPT-2 tokenizer  
3. The GPT-2 model generates new tokens using probabilistic sampling  
4. Generated tokens are decoded into readable text  
5. Output is displayed to the user in real time  

---

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
pip install -r requirements.txt
▶️ Running the Application

Execute the application locally:

python app.py


For Google Colab or remote execution:

interface.launch(share=True)

🧪 Sample Usage
Input Prompt
Once upon a time in a small village

Generated Output
Once upon a time in a small village, there lived a young boy who dreamed of adventure...


Results may vary depending on temperature and token settings.

⚠️ Limitations

Generated content may be biased or factually incorrect

Output quality depends on prompt design

Not suitable for critical or sensitive applications

🔮 Future Enhancements

Deployment on Hugging Face Spaces with GPU support

Text history and export functionality

Integration of larger and more advanced language models

UI performance and design improvements

📜 License

This project is developed strictly for educational and learning purposes.

👩‍💻 Author

Sreeja
BSc Artificial Intelligence & Machine Learning
Academic Mini Project



