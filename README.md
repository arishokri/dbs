### Docker Compose for Popular DBs

Following dbs are included:
- PostgreSQL
- MongoDB
- ChromaDB
- ElasticSearch

Additional chromaDB configs are provided in a separate yaml file and bound to the container drive.

#### To run:

Put a chosen password (to be shared among your db instances) and put it into the `.env` file and then run `docker-compose up -d`.