# Automated Email Response Generator

This project implements an **Automated Email Response Generator** using **LangChain**, **LangGraph**, and **Groq's LLM**. It automates the process of classifying incoming emails and generating suitable responses based on their content.

## Features

- **Email Classification**: Automatically classify incoming emails into categories like Inquiry, Complaint, Follow-Up, etc.
- **Response Generation**: Generate appropriate email responses based on the category and content.
- **State Management**: Manage the workflow of email classification, response generation, and termination using LangGraph.
- **LLM Integration**: Leverage Groq LLM to generate human-like email responses.

## Tech Stack

- **Python**
- **LangChain**
- **LangGraph**
- **Groq LLM**
- **Dotenv** for managing environment variables

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables by creating a `.env` file in the root directory:

   ```plaintext
   GROQ_API_KEY=<your-groq-api-key>
   ```

## Usage

1. Run the Jupyter Notebook to initiate the email response generation process.

2. The notebook follows a multi-step process:

   - **Input Email**: Provide the email content.
   - **Classify Email**: The system classifies the email into a category (like Inquiry, Complaint, etc.).
   - **Generate Response**: The LLM generates an appropriate response based on the category.
   - **Display Response**: The generated response is displayed for review.

3. The output will include:

   - **Email Content**
   - **Email Category**
   - **Generated Response**

## Example Workflow

1. **Input Email**: "I want to know the status of my order."
2. **Classify Email**: Category: Inquiry
3. **Generate Response**: "Thank you for reaching out. Your order is being processed."
4. **Display Response**: The response is shown in the notebook output.

## Environment Variables

Ensure you set the following environment variable in your `.env` file:

```plaintext
GROQ_API_KEY=<your-groq-api-key>
```

