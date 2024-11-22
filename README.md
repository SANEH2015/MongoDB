<img src="https://socialify.git.ci/SANEH2015/MongoDB/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="MongoDB" width="640" height="320" />
<h1># MongoDB</h1>

This project demonstrates the creation and management of a MongoDB database named Codetribe. It is designed to help trainees understand key MongoDB concepts, such as databases, collections, and documents, while working with JSON-like data.

The database includes three collections: Facilitators, Trainees, and Projects, each containing sample data relevant to an educational or training environment.

Action	                                 Command
Start MongoDB                                   shell	mongosh
Switch to a database	                           use Codetribe
Insert a document	                               db.CollectionName.insertOne({...})
View all documents	                                 db.CollectionName.find().pretty()
List databases	                                    show dbs
List collections	show collections

## Run Locally

Clone the project
```bash
  git clone https://github.com/Amniei/Shopping-List.git
```
start MongDB

  mongosh
```
Switch to a Database

  use Codetribe
```
Insert a document
```
  db.CollectionName.insertOne({...})
```
