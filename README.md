# Finance Help Chatbot

Welcome to the Finance Help Chatbot! This application provides financial advice specializing in Indian finance, covering various domains such as personal finance, investments, taxation, real estate, and retirement planning. The chatbot leverages a language model to offer accurate, insightful, and personalized financial advice.

## Features

- **User-friendly Interface**: Easy to navigate and interact with the chatbot.
- **Detailed Financial Advice**: Provides comprehensive responses to finance-related queries.
- **Interactive Chat**: Engage in a conversational manner to get follow-up answers.
- **Instructions and Guidelines**: Clear instructions to help users interact effectively with the chatbot.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.8+
- Pip (Python package installer)
- Docker (if using Docker for deployment)
- Streamlit
- An Azure account with an 8GB instance

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Saksham-21/Ollama-based-financial-Chatbot.git
    cd Ollama-based-financial-Chatbot
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

### Deployment

To deploy the application on an Azure instance:

1. **Create an Azure VM**:
    Set up an Azure VM with at least 8GB of RAM.

2. **Transfer your project to the Azure VM**:
    - *Git clone*:
        ```bash
        git clone https://github.com/Saksham-21/Ollama-based-financial-Chatbot.git
        cd Ollama-based-financial-Chatbot
        ```
    


3. **Install dependencies on the Azure VM**:
    SSH into your Azure VM and install the necessary dependencies as described.

    - **Building up Docker-compose**:
         ```bash
         sudo docker-compose build
         ```
    - **Starting Up Docker-compose**:
         ```bash
         sudo docker-compose up -d 
         ```    
4. **Download the Phi model from ollama**:
    ```bash
    docker exec -it ollama-container ollama run phi
    ```

5. **Access the application**:
    Navigate to your Azure VM's public IP address to access the deployed application.

## Usage

1. **Ask a question**:
    Enter your finance-related question in the sidebar and click 'Enter'.

2. **View the response**:
    The chatbot will provide a detailed response. You can continue the conversation by entering follow-up questions in the chat panel.

3. **Instructions**:
    Refer to the "Instructions" expander for detailed guidelines on how to interact with the chatbot.

## Contributing

1. **Fork the repository**:
    Click on the 'Fork' button at the top right of this page to create a copy of this repository in your account.

2. **Clone your forked repository**:
    ```bash
    git clone https://github.com/Saksham-21/Ollama-based-financial-Chatbot.git
    ```

3. **Create a new branch**:
    ```bash
    git checkout -b feature-branch
    ```

4. **Make your changes**:
    Add your changes or new features.

5. **Commit your changes**:
    ```bash
    git add .
    git commit -m "Add your message"
    ```

6. **Push to the branch**:
    ```bash
    git push origin feature-branch
    ```

7. **Create a Pull Request**:
    Go to your forked repository on GitHub and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Saksham-21/Ollama-based-financial-Chatbot/blob/main/LICENSE) file for details.

## Acknowledgements

- [Streamlit](https://www.streamlit.io/) for providing an easy-to-use web framework.
- [Ollama](https://www.ollama.com/) for the language model.

## Contact

For any questions or suggestions, please contact [Sakshamsingla21@gmail.com].