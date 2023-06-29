# PyRetrieverGPT
This interactive Python application uses OpenAI and the Langchain library to retrieve and respond to user queries. It is primarily designed for retrieving information from a dataset and presenting it in an engaging, user-friendly manner.

# Features
Interactive Command Line Interface (CLI): The application uses Typer to allow users to interact with the system via the command line in a conversational manner.
Rich Text Output: The Rich library is used to format the console output, enabling the display of tables and colorized text.
Information Retrieval: Leveraging the Langchain library, this application creates a semantic search index from a provided dataset (located in the "mydata" directory). It uses this index to retrieve relevant responses to user queries.
Persistency: The application can optionally persist the semantic search index to disk, enabling faster startup times for subsequent runs.

# Usage
1. Locate the file(s) to read in the mydata folder. Files can be txt, pdf, docx, xls, html.
2. Run the Python application. You will be welcomed with a table showing available commands.
3. To ask a query, type it at the >> prompt and press enter. The application will return the relevant response.

To start a new query, type new at the >> prompt.

To exit the application, type exit at the >> prompt.

# Dependencies
OpenAI: To generate semantic embeddings and responses.
Langchain: For handling the creation and management of the semantic search index.
Typer: To handle the interactive command line interface.
Rich: To format console output.

Please refer to the requirements.txt file for a complete list of dependencies.

Note: You need to set your OpenAI API Key in the credentials.py file for the application to run properly.
