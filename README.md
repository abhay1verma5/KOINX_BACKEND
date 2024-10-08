
# -------------follow step wise-------
### `git clone https://github.com/abhay1verma5/KOINX_BACKEND`
#   `KOINX_BACKEND`

### `npm install`

### `npm run dev`


This project is a backend service implemented using Node.js, Express.js, and MongoDB. It interacts with the Ethereum blockchain to perform the following tasks:

- Fetch transactions by wallet address.
- Get the current balance of a given Ethereum wallet in both ETH and INR.
- Schedule a task to collect Ethereum prices periodically.
- Implement CRUD operations for managing transactions and Ethereum price data.
- Key Technologies Used
- Node.js: JavaScript runtime for building the backend service.
- Express.js: Framework for building web applications and APIs.
- MongoDB: NoSQL database to store transactions and Ethereum price data.
- Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js.
- Cron: Task scheduler to automate price collection jobs.
- Axios: Promise-based HTTP client for making API requests.
- dotenv: Module to load environment variables from a .env file.
