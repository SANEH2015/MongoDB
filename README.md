
<img src="https://socialify.git.ci/SANEH2015/MongoDB/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="MongoDB" width="640" height="320" />
MongoDB: Codetribe Database Project
This project demonstrates the creation, management, and export of a MongoDB database named Codetribe. It serves as a hands-on activity to help trainees understand MongoDB concepts, such as databases, collections, and documents, while learning to manage JSON-like data.

The Codetribe database includes three collections: Facilitators, Trainees, and Projects, each containing sample data relevant to an educational or training environment.

Run Locally

Follow these steps to replicate the project on your local machine:

1. Clone the Project
2. 
Clone this repository:

bash
Copy code

git clone https://github.com/Amniei/MongoDB.git
2. Navigate to the Project Directory
Move to the project's directory:

bash
Copy code
cd MongoDB
3. Restore the Database

Use the following command to restore the database from the exported BSON files:

bash
Copy code
mongorestore --db=Codetribe ./Codetribe
This will import the Facilitators, Trainees, and Projects collections into your MongoDB instance.

4. Start the MongoDB Shell
5. 
Open the MongoDB shell to interact with the database:

bash
Copy code
mongosh
Switch to the Codetribe database:

javascript
Copy code
use Codetribe
5. Query the Data
You can view the data in each collection using the following commands:

Facilitators:
javascript
Copy code
db.Facilitators.find().pretty()
Trainees:
javascript
Copy code
db.Trainees.find().pretty()
Projects:
javascript
Copy code
db.Projects.find().pretty()
