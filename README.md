<img src="abibas.jpg" align="left" width="40" height="40"> 
<br/>

# Abibas System Design Capstone

The goal of the Abibas System Design Capstone is to scale legacy code and optimize query times by restructuring the architecture of the server and database and comparing a relational with a non-relational database. The team of engineers compared the cost benefit analysis of horizontal and vertical scaling. 


## Tech Stack

- MongoDB
- PostgreSql
- Express
- Node.Js
- Docker
- NginX
- Redis
- EC2
- Amazon Load Balancer
- Artillery
- Jest
- Loader.io
- Webpack
- React

## Features 

- Optimized the system design of a database with 10,000,000 products by analyzing relational/non-relational database throughput and query times

- Reduced the query latency by 20x to 3ms through horizontally scaling with multiple servers, load balancing, indexing and utilizing promises 

- Increased the throughput of API calls from 250rps to 3000rps with 0% error rate

- scaled server and database horizontally using load balancing with NginX to utilize 6 servers

## Development

### Installing Dependencies

From within the root directory:

1. Install dependencies
```sh
npm install
  ```
2. Build project
```sh
npm run build
  ```
3. There are two server options 

To Start Postgres Server:
- npm postgresStart 

To Start Mongo Server:
- npm mongoStart