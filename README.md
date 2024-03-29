# Neo4j Graph Database and Recommendation System:

**Problem:**
The project required the integration of a Neo4j graph database and a recommendation system to facilitate efficient search and recommendation functionalities based on user input. Specifically, the project aimed to display components based on user search queries, necessitating the use of Neo4j for CRUD (Create, Read, Update, Delete) operations on sheets stored in CSV files, along with their associated metadata and values. Additionally, the project required the implementation of a basic recommendation system to provide users with relevant suggestions.

**Resolution:**
To address these requirements, the following steps were undertaken:
1. **Neo4j Graph Database Setup:** A Neo4j graph database was set up to store and manage data extracted from CSV files. This involved creating nodes and relationships within the graph to represent the data structure effectively.
2. **CRUD Operations Script:** A script was developed to perform CRUD operations on the Neo4j graph database using the Neo4j driver. This script included functionality to connect to the Neo4j database, load data from CSV files into the graph as nodes and relationships, and implement functions for CRUD operations such as adding, retrieving, updating, and deleting data.
3. **Recommendation System Implementation:** For the recommendation system (since the project was new-basic content-based filtering was implemented), the Neo4j graph database was utilized to leverage indirect relationships between nodes for making recommendations. By analyzing the graph structure and traversing relationships, the recommendation system generated suggestions based on similarities or associations between components.
4. **Integration with Frontend:** The CRUD operations script and recommendation system functionality were integrated into the frontend application. User input from search queries was processed, and relevant data was retrieved from the Neo4j graph database to display matching components. Additionally, recommendations generated by the recommendation system were presented to users based on their interactions with the application.

Through the integration of a Neo4j graph database and a recommendation system, the project successfully addressed the requirement to display components based on user search queries and provide relevant recommendations. The use of Neo4j facilitated efficient CRUD operations on data stored in CSV files, while the recommendation system utilized the graph structure to offer personalized suggestions to users. Overall, the project achieved its objectives of enhancing user experience through effective data management and recommendation functionalities.


(**Note:** Due to organization's confidentiality, the project code and screenshots cannot be uploaded to GitHub.)
