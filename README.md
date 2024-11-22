<img src="https://socialify.git.ci/SANEH2015/MongoDB/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="MongoDB" width="640" height="320" />
<h1># MongoDB</h1>

This project demonstrates the creation and management of a MongoDB database named Codetribe. It is designed to help trainees understand key MongoDB concepts, such as databases, collections, and documents, while working with JSON-like data.

The database includes three collections: Facilitators, Trainees, and Projects, each containing sample data relevant to an educational or training environment.

<h5>Prerequisites</h5>

MongoDB installed on your system.

MongoDB shell (mongosh) set up and accessible in your terminal.

## Run Locally

Clone the project
```bash
  https://github.com/SANEH2015/MongoDB.git
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
Veiw all document
```
  db.CollectionName.find().pretty()
```
List databases
```
  show dbs
```
List collections 
```
  show collection
```
