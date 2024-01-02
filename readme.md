To run this app:
1. Open pgAdmin and create a 'world' database, then create table 'capitals':
    CREATE TABLE capitals (
        id SERIAL PRIMARY KEY,
        country TEXT,
        capital TEXT
    )
2. import the capitals.csv file into the table we just created
3. run 'node index.js' in terminal and open localhost:3000 to view
