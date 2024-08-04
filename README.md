# Quiz Generator and Manager

This project is a comprehensive quiz generation and management application built using Streamlit. It utilizes various tools and technologies such as Large Language Models (LLMs), document processing, and vector stores for effective quiz creation and user interaction.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)


## Introduction

The Quiz Generator and Manager is designed to automatically generate quizzes based on provided topics and documents. It integrates various tasks, such as document processing, embedding creation, and quiz management, to create an interactive and user-friendly quiz application.

## Features

- **Document Processing**: Ingests and processes PDFs to extract relevant information.
- **Embedding Creation**: Uses embeddings to create a vector store for document retrieval.
- **Quiz Generation**: Automatically generates quiz questions based on the provided topic.
- **Quiz Management**: Manages quiz navigation and user interaction.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/quiz-generator-manager.git
    cd quiz-generator-manager
    ```

2. Set up a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```


## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run task_10.py
    ```

2. Follow the instructions on the web interface to upload documents, specify the quiz topic, and generate quizzes.

3. Navigate through the generated quiz using the provided interface.

## Project Structure

```
.
├── task_3.py
├── task_4.py
├── task_5.py
├── task_8.py
├── task_9.py
├── main.py
├── requirements.txt
└── README.md
```

- `task_3.py`: Handles document processing.
- `task_4.py`: Manages embedding creation.
- `task_5.py`: Creates Chroma collections for the vector store.
- `task_8.py`: Contains the QuizGenerator class for generating quiz questions.
- `task_9.py`: Contains the QuizManager class for managing the quiz.
- `task_10.py`: Main entry point for running the Streamlit application.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **Python**: Core programming language.
- **LangChain**: Utilized for integrating LLMs and creating embeddings.
- **Chroma**: Used for creating and managing vector stores.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
6. Open a pull request.

