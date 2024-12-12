# NodeJS LocalLibrary
This library is a big storage for resonable tasks.

## For this project you should:
- Install NodeJS v14+
- Install npm
- MongoDB Server


## Installation guide
1. Clone this repository
        ```
        git clone https://github.com/goncharovchik/LocalLibrary.git
        ```
2. Install dependencies
    ```
    cd LocalLibrary
    npm i
    ```
3. Install or deploy mongoDB database
    Use populatedb.js for create tables in DB.
    By command:
    ```
    node populatedb.js [db_connection_url]
    ```
4. Set Environments
    ```
    MONGO_DB='your_connection_url_to_mongo_db'
    ```
4. Run project
    
    For production:
    ```
    npm run start
    ```

    For develop:
    ```
    npm run devstart
    ```