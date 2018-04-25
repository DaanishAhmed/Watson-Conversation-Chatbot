Chatbot Implementation on Ice Cream Shop Transactions
----------------

This project involves using IBM Watson Conversation to build a chatbot that manages an online store for a fictional ice cream shop.  The goal of the chatbot is to process transactions and answer user questions about products, order methods, or store locations.  The chatbot is designed to simulate a more human level of transaction, which it achieves by remembering the user's name, storing their existing order information, and using variations of each response.  The bot allows for the user to order online or visit a physical store.  If the user wants to shop online, the bot will ask for their order, compute the order price, and ask for order confirmation.  If the user wants to visit an actual store, the bot will ask for their state of residence and list all open locations in that state.

The full report can be found in the file "Chatbots.pdf".  This report shows a complete breakdown of my chatbot implementation, including problem description, motivation, implementation steps, process flow description, analysis and chatbot tuning, and recommendations for further improvement.  Tables and visualizations are featured in the main body of the text.

The project involved creating intents and entities to handle the user queries and store important information.  These are included in the main JSON file, but I have also uploaded them separately for reference.  They are found in the files "intents.csv" and "entities.csv."

The dialog itself is included in the JSON file "Chatbot_IceCreamShop.json".  The requirements are described in the file "requirements.txt".  To access the project, you need to import the JSON file into Watson Conversation as a new workspace.