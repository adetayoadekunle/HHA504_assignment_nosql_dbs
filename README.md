# HHA504_assignment_nosql_dbs
## Database creation and Configuration Process:
### BigQuery:
#### Created project name, dataset called healthcare data, and a table called nosql_hw
![GCP BigQuery Part 1](https://github.com/user-attachments/assets/181fd609-0efa-4db7-8fa3-6d47c11e795e)
![GCP BigQuery Part 2](https://github.com/user-attachments/assets/83f3d496-cf6c-4995-8d32-3c309000b478)
![GCP BigQuery Part 3](https://github.com/user-attachments/assets/11981e63-7111-489e-8ff5-24b91395337d)
![GCP BigQuery Part 4](https://github.com/user-attachments/assets/a9f402e7-80cc-44f6-b87e-81ed1f279bfb)

### MongoDB Atlas:
#### Fake dataset loaded into MongoDB Atlas from Google Colab
![MongoDB Atlas Start and Configure Databases Part 1](https://github.com/user-attachments/assets/66182608-b72c-47c3-8e42-6457220badb5)
![MongoDB Atlas Start and Configure Databases Part 2](https://github.com/user-attachments/assets/2d3a8adc-c73e-4b66-98cf-40408741517e)
![MongoDB Atlas Start and Configure Databases Part 3](https://github.com/user-attachments/assets/a2601a4f-602e-488e-b87d-8894ef9594ed)
![MongoDB Atlas Start and Configure Databases Part 4](https://github.com/user-attachments/assets/b2b3b725-bb3e-4006-b65e-d486f05a7f2c)

### Redis Cloud:
#### Connect to Redis Cloud and patient data is inserted into Redis. Also, being able to enter patient ID to retrieve specific information.
![Redis Cloud Part 1](https://github.com/user-attachments/assets/943ff8ec-804a-49a9-a846-fd36e9caefa1)
![Redis Cloud Part 2](https://github.com/user-attachments/assets/eee367c0-1402-4c14-8fc1-f66434e22e15)
![Redis Cloud Part 3](https://github.com/user-attachments/assets/823b3ac1-6520-4d9d-993d-bc0e8e707caf)


## SQL RUN in BigQuery and the results:
![GCP BigQuery Part 2](https://github.com/user-attachments/assets/83f3d496-cf6c-4995-8d32-3c309000b478)
![Explore BigQuery (Monitor Usage and Cost) Part 1](https://github.com/user-attachments/assets/c04326aa-4d25-4862-9f51-9634fdce6c4f)

## Modify and Explore the Data in MongoDB Atlas and Redis Cloud:
### Mongo DB Atlas:
#### Dataset inserted to MongoDB Atlas. PatientID and VisitDate (unique dentifiers and data types). MongoDB Atlas document inserted. A simple query ran to retrieve patient data based on a condition (Age > 60)
![Modify and Explore Data in MongoDB Atlas (Greater Than 60) Part 2](https://github.com/user-attachments/assets/7392a7f0-4271-4af1-b313-ead5b443eca2)
![Modify and Explore Data in MongoDB Atlas Part 3 (Insert Document)](https://github.com/user-attachments/assets/42e64c5c-e76f-40cb-8e5b-62c9820da8f2)
### Redis Cloud:
#### PatientID is key, and the rest of the patient data is the value. Patient 6 is used as an example. All data retrieved for PatientID = 1
![Redis Cloud Modify and Explore Data Part 4](https://github.com/user-attachments/assets/58dcd2de-9975-410d-bec3-7bc4ab461720)
![Redis Cloud Modify and Explore Data Part 5](https://github.com/user-attachments/assets/e6b410c8-3b7c-4912-86d1-a96e94fc8c99)
![Redis Cloud Modify and Explore Data Part 6](https://github.com/user-attachments/assets/ceb0d11d-64a1-4ab3-a089-b75e0deafe61)


## Documentation of experience and reflections working on each platform (BigQuery, MongoDB Atlas, Redis Cloud):
I set up BigQuery through Google Console and created a project, dataset, and table. The setup was easy and smooth, and the interface was easy to read and use. Also, the query editor was easy to use because I could test SQL queries with no issues. It was a great experience, but I had problems finding the cost management when running queries in the query editor.
I set up MongoDB Atlas using the free-tier cluster, used google colab to send the fake dataset to Cloud.monngo.com, and named it Healthcaredabatase.patients. Visually, it was easy to see the fake data set under collections that can show data such as PatientID and age. Overall, the experience of using MongoDB Atlas was an easy experience of using.
I set up Redis Cloud using the free tier Redis instance. I used Redis CLI to connect to the database. I implemented it with google colab to produce different results such as retrieving data for a patient. Overall, it was a good experience to use due to the dashboard being easy to use but I think there should be a way to test queries on the free tier on the Redis Cloud site.
