<img width="1236" alt="image" src="https://github.com/ggandia-xtillion/xtillion-dais-hackathon-24/assets/155562434/47408769-7ec2-4f48-8795-6ef61297c8c9"># xtillion-dais-hackathon-24

# Project Title
Pathways to Empowerment: Bridging Resources for Immigrant Women in the San Francisco Bay Area

# Project Description
Our mission is to provide vital assistance to immigrant women in the San Francisco Bay Area by connecting them with the resources they need to overcome challenges and thrive. Through an interactive and user-friendly chatbot, individuals can seek guidance on a wide range of topics, from legal aid to community support services, empowering them to navigate their journey with confidence and resilience.

# Repository Contents

Within this repository, you'll discover:

1. scraper.ipynb: This notebook scrapes information from various websites containing legal resources for immigrants in the Bay Area, compiling the content into a structured JSON format.

2. website_contents.json: A comprehensive JSON file containing the scraped content, serving as the foundation for our chatbot's knowledge base.

3. Rag.ipynb: This notebook utilizes the Retrieve and Generate (RAG) model, powered by Large Language Models (LLMs), to create an interactive chatbot experience. The steps involved in this process include:

    Setting up a vector index and configuring it to leverage an embedding model from the FMAPI for generating embeddings.
    Loading text data into the vector database.
    Querying the database to retrieve relevant information.
    Constructing prompts for LLMs based on the query results.
    Querying an LLM via the FMAPI using the generated prompts, ensuring accurate and contextually relevant responses to user inquiries.
Through these meticulously crafted components, our project provides a seamless and impactful solution for immigrant women in the San Francisco Bay Area, offering a pathway to empowerment and access to essential resources.

