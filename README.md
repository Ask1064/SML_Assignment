# Bank Statement Query Agent
## Overview
The Bank Statement Query Agent is a project designed to interact with a SQL database to answer questions about bank statements. Utilizing LangChain, SQLAlchemy, and SQLite, this agent processes and queries financial data to provide insightful responses.

## Features
 - **SQL Database Interaction**: Query a local SQLite database containing bank statement data.
 - **Natural Language Processing**: Use a language model to translate natural language questions into SQL queries.
 - **Local Processing**: All data processing and model inference are performed locally.

![image](https://github.com/Ask1064/SML_Assignment/assets/126004769/efdcf590-c2cc-4582-8b0c-c660e33927d0)
## Setup Instructions
### Prerequisites
Ensure you have the following installed on your system:

 - Python 3.8 or higher
 - SQLite

### Installation Steps
1. Clone the repository
```sh
git clone https://github.com/yourusername/bank-statement-query-agent/
```
2. Navigate to the project directory
```sh
cd bank-statement-query-agent
```
3. Set up a virtual environment
```sh
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```
4. Install project dependencies
```sh
pip install -r requirements.txt
```
### Running the Application
To run the Jupyter Notebook and start interacting with the SQL database, follow these steps:

1. **Launch Jupyter Notebook**
```sh
jupyter notebook
```
2. **Open the main notebook**

In your web browser, navigate to the main_ntbk.ipynb notebook.
Follow the instructions in the notebook to interact with the bank statement data.

## Usage
### Creating the Sample Database
The project includes a script to create and populate a sample SQLite database (bank_statement.db) with bank statement data. The script is included in the main_ntbk.ipynb notebook.

### Querying the Database
Use the notebook interface to input natural language questions. The agent will translate these questions into SQL queries and provide the results.

Project Structure
```
├── main_ntbk.ipynb
├── bank_statement.db
├── requirements.txt
└── README.md
```
## Additional Notes
1. Ensure that your system has sufficient resources (CPU, RAM) to handle the processing.
2. If you encounter any issues, please refer to the official documentation of the respective tools and frameworks being used.
