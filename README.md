# n8n-chatbot

this chatbot activates when the user sends a message to the chatbot. it then retrieves the data from the google cloud and stores them in a pinecone database. It then calls on a 4o-mini chatgpt model to read the files retrieved, and provide appropriate answers for the user. If the model is unable to answer, it responds with "I don't know".
