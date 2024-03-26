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
2. Track this if you want it to be added to hasira
3. You should now be able to use api and query via console
4. Push everything to github

## Create and configure Hasura cloud project
1. Log onto hasura cloud and create a new poject 
2. You will need to provision a pg db on a cloud platform (digital ocean is the cheapest)
3. Add environment variable with db connections details of postgres db on hasura cloud
4. Click Launch console
5. Click Data and connect existing db, select post gress and past in environment variable name PG_DATABASE_URL
6. Going back to cloud.hasura.io overview page for proiject click on git deploy and sign in
