Introduction

The aim of this experiment is to develop an AI chatbot using a Large Language Model (LLM). The chatbot accepts questions from users and generates meaningful responses using a pretrained language model. Python is used for implementation, Hugging Face Transformers is used to load the model, and Gradio is used to create an interactive user interface. The chatbot is designed to answer different types of questions in clear and understandable language.

Environment Setup and Model Selection

The development environment is prepared by installing the required Python libraries, including PyTorch, Transformers, and Gradio. A pretrained instruction-following model, Qwen2.5-1.5B-Instruct, is selected to generate responses to user questions. The model and tokenizer are loaded using the Hugging Face Transformers library. A sample prompt is used to verify that the model can generate a response before integrating it into the chatbot interface.

Paragraph 3: Chatbot Implementation and Testing

A chatbot function is created to accept user messages, process the complete question, and generate an appropriate response. The generated tokens are converted into readable text and displayed through the Gradio interface. Conversation history can be maintained to help the chatbot understand follow-up questions. The chatbot is tested using at least five questions related to Artificial Intelligence, Python, Machine Learning, chatbots, and Natural Language Processing to evaluate the relevance and readability of its responses.

Paragraph 4: Deployment and Conclusion

The chatbot is executed in the development environment and accessed through a web browser using the Gradio interface. Its responses are evaluated to identify incorrect, incomplete, repetitive, or irrelevant information. The source code, README file, screenshots, and sample outputs are prepared for submission, along with the GitHub repository and application links when available. This experiment demonstrates how pretrained language models can be integrated with a user-friendly interface to build an interactive chatbot, while highlighting the importance of testing, security, and responsible use of AI-generated responses.

# 24ADI006_RAMYA-R_24BAD096_EX_10
