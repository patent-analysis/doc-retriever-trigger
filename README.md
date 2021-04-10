# doc-retriever-trigger
Scripts to trigger extracting the uspto-doc-retriever to extract the historical documents

## Description
The postman collection requests in this repo are used to trigger the uspto-doc-retriever to extract the bulk document data for a spescific week's archive data. 

To trigger any given year, load the postman collection and years environment file and run the collection using postman runner.
Notes:
Environment variables that have to be set
`API_ID` is the API gateway API ID (this can be found in the output of the uspto-doc-retriever)
`WEEK_NUM` is the week to extract
`YEAR_NUM` is the year number to extract

## Repo Structure
```bash
.
├── README.md                 <-- This readme file
├── CollectionData            <-- Folder Holding the Years and Weeks to extract
└── APIRequests               <-- Folder holding the postman collection
```