# RAG-Enabled PDF Q&A System Project

A Streamlit application that uses RAG (Retrieval-Augmented Generation) and LangChain to answer questions from PDF files. Chat with your PDF files and ask the most specific questions about them!

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Docker Container](#docker-container)
- [Streamlit UI](#streamlit-ui)
- [CI/CD Pipeline](#ci-cd-pipeline)
- [Contributing](#contributing)
- [License](#license)

## Features

- Upload a PDF file
- Process the PDF file and store the text in a vector database
- Ask questions about the PDF content using natural language
- Get answers from the vector database using LLMs (Language Models)

## Streamlit UI

The Streamlit UI allows users to:

- Upload a PDF file via the provided file upload interface.
- Enter questions about the PDF content using a text input box.
- View answers retrieved from the vector database, displayed in a user-friendly format.

## CI/CD Pipeline

This project includes a CI/CD pipeline using GitHub Actions. The pipeline performs the following actions:

- Lints the Python code using `flake8`.
- Runs the tests using `pytest`.
- Builds and pushes a Docker image to Docker Hub.
- Deploys the Docker image to Heroku.

To use the CI/CD pipeline, create a new repository on GitHub and push your code to the `main` branch.
