# xtillion-dais-hackathon-24

# Project Title
Pathways to Empowerment: Bridging Resources for Immigrant Women in the San Francisco Bay Area

# Project Description
Our mission is to provide vital assistance to immigrant women in the San Francisco Bay Area by connecting them with the resources they need to overcome challenges and thrive. Through an interactive and user-friendly chatbot, individuals can seek guidance on a wide range of topics, from legal aid to community support services, empowering them to navigate their journey with confidence and resilience.

# Repository Contents

Within this repository, you'll discover:

1. scraper.ipynb: This notebook scrapes information from various websites containing legal resources for immigrants in the Bay Area, compiling the content into a structured JSON format.

The resources focus on websites within the following topics:
- General Information on Domestic Violence
- Domestic Violence in Gay/Lesbian Relationships
- Domestic Violence – Religion
- Domestic Violence – Batterer Intervention
- Housing
- Health and the Medi-Cal Program
- California’s Medi-Cal Program
- Immigration Resources; Deferred Action of Childhood Arrivals (DACA)
- California Work Opportunities and Responsibility to Kids (CalWORKs)
- Food Stamp and Nutrition Programs
- Supplemental Security Income (SSI)
- Unemployment Insurance
- Legal Information for Individuals and Families Impacted by Northern California Wildfires
- Legal Research

3. website_contents.json: A comprehensive JSON file containing the scraped content, serving as the foundation for our chatbot's knowledge base.

4. Rag.ipynb: This notebook utilizes the Retrieve and Generate (RAG) model, powered by Large Language Models (LLMs), to create an interactive chatbot experience. The steps involved in this process include:

    Setting up a vector index and configuring it to leverage an embedding model from the FMAPI for generating embeddings.
    Loading text data into the vector database.
    Querying the database to retrieve relevant information.
    Constructing prompts for LLMs based on the query results.
    Querying an LLM via the FMAPI using the generated prompts, ensuring accurate and contextually relevant responses to user inquiries.
Through these meticulously crafted components, our project provides a seamless and impactful solution for immigrant women in the San Francisco Bay Area, offering a pathway to empowerment and access to essential resources.

