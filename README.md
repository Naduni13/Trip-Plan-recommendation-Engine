# Trip-Plan-recommendation-Engine
According to user preference generate a Trip plan
# Flask API with Sentence Transformers and Pinecone

This project implements a Flask-based API that utilizes sentence transformers for generating embeddings and Pinecone as a vector database. The API is designed to run in Google Colab with ngrok for public tunneling.

## Features

- Sentence embedding generation using Sentence Transformers
- Integration with Pinecone vector database
- Flask-based REST API endpoints
- ngrok tunneling for public access
- Designed for Google Colab environment

## Prerequisites

Before running this project, you'll need:

- Google Colab account
- ngrok account and auth token
- Pinecone API key (if using Pinecone database)
- Python 3.6+

## Installation

1. Clone or upload the notebook to Google Colab
2. Ensure you have the required authentication tokens:
   - ngrok auth token (added in the first cell)
   - Pinecone API key (if applicable)

## Setup

The notebook includes all necessary installation commands:

```bash
!pip install pyngrok sentence-transformers pinecone-client transformers requests numpy flask-ngrok pyngrok pinecone
