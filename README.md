# hasura-vercel
Familiarizing myself with Hasura and Vercel to test drive dev experience

## Setup
1. hasura init (project name: hasura)
2. curl https://raw.githubusercontent.com/hasura/graphql-engine/stable/install-manifests/docker-compose/docker-compose.yaml -o docker-compose.yml
3. docker-compose up -d
4. cd hasura
5. hasura console
6. click on data and "connect database"
7. Select DB (postgress) and connect exist database
8. Copy environment variable name PG_DATABASE_URL also found in docker-compose file 


## Updating schema and working with Hasura
1. Click on Data and schema and paste the sql schema to add tables to postgress db
2. Track this if you wantit to be added to hasira
