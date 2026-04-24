# MongoEstudiantes
🍃 MongoDB Exercise – Students CRUD Application
📋 Description
This project is an individual activity focused on practicing NoSQL database management using MongoDB Atlas and MongoDB Compass, connected to Python via PyMongo. The exercise implements a basic CRUD (Create, Read, Update, Delete) menu-based application to manage a student collection (BD_CursoMongo.Estudiantes).

📁 Repository Contents
FileDescriptionmongodb_for_all.ipynbJupyter Notebook with the full CRUD implementationBD_CursoMongo.Estudiantes.jsonSample dataset with student recordsREADME.mdThis file

⚙️ Setup & Requirements
bashpip install --upgrade pymongo
Replace the connection string in the notebook with your own MongoDB Atlas URI:
pythoncliente = MongoClient("mongodb+srv://<user>:<password>@<cluster>.mongodb.net/")

🚀 Features
The application presents an interactive menu with the following options:
--- MENÚ DE ESTUDIANTES ---
1. Insert student
2. List students
3. Update student's age
4. Delete student
5. Exit
Each option maps to a PyMongo function (insert_one, find, update_one, delete_one).

☁️ Interaction with MongoDB Atlas

[Describe your experience here — example below, edit as needed]

MongoDB Atlas was used to host the cloud cluster. After creating a free-tier cluster, I obtained the connection string from the Connect menu and pasted it into the notebook. I configured network access to allow connections from my IP address. The ping command was used to verify the connection was successful before running any CRUD operations. All data inserted through the notebook was visible in real time on the Atlas web interface under the BD_CursoMongo database and Estudiantes collection.

🧭 Interaction with MongoDB Compass

[Describe your experience here — example below, edit as needed]

MongoDB Compass was used as a local GUI to visually inspect and manage the data. I connected it using the same Atlas connection string. Through Compass I was able to browse the Estudiantes collection, verify that inserted documents appeared correctly, apply filters to query specific records, and confirm updates and deletions made via the notebook. Compass made it easy to visualize the document structure without writing additional queries.

📊 Dataset
The collection contains 18 student records from the Ciencia de Datos program, each with the following structure:
json{
  "_id": { "$oid": "..." },
  "nombre": "Ailyn Gomez",
  "edad": 19,
  "carrera": "Ciencia de datos"
}

🔗 Submission

GitHub Repository: [paste your repo link here]
Submission Form: [paste the Google Forms link here]


👤 Author
Ailyn Gomez
Ciencia de Datos
Individual activity — MongoDB Atlas & Compass Workshop
