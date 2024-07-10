# Transportation Query Chatbot

This is a web-based chatbot application designed to answer transportation-related queries using an LLM (Microsoft-Phi-3-mini-128k) with a Retrieval-Augmented Generation (RAG) implementation.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Backend](#backend)
  - [Dependencies](#dependencies)
  - [Running the Backend](#running-the-backend)
- [Frontend](#frontend)
  - [Dependencies](#dependencies-1)
  - [Running the Frontend](#running-the-frontend)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project is a chatbot application that uses the Microsoft-Phi-3-mini-128k model to generate answers to user queries about transportation. It leverages Retrieval-Augmented Generation (RAG) to provide accurate and contextually relevant responses.

## Features

- Real-time query processing
- Retrieval-Augmented Generation (RAG) for enhanced answer accuracy
- Interactive and responsive user interface

## Tech Stack

- **Model**: Microsoft-Phi-3-mini-128k
- **Backend Framework**: FastAPI
- **Frontend Framework**: React + Vite
- **CSS**: Tailwind, Material-Tailwind, hover.dev

## Setup

To get the project up and running, follow these steps:

### Backend

#### Dependencies

All necessary dependencies for the backend are listed in the `requirements.txt` file located in the `backend` folder. To install them, run:

```bash
pip install -r backend/requirements.txt

cd backend

uvicorn main:app --reload
```

### Frontend

#### Dependencies

Install the required dependencies for the frontend by navigating to the frontend folder and running:

```bash
Running the Frontend
Navigate to the frontend directory:
cd frontend

Start the Vite development server:
npm run dev

```
### Contributions
```bash
Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.
```
### License
This project is licensed under the MIT License. See the LICENSE file for more details.
```bash

Feel free to adjust any part of the content to better suit your needs.

```
