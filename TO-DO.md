# To Do List for Project
1/4/26: still working on scrapinf data from FBref, looking into StatsBomb (data provider/company behind FBref) and their API/python package statsbombpy. In the meantime pull data they have available from their opendata git repository

- setup DuckDB database for data pulled from statsbomb open data repository
- pipe JSON data into DuckDB database
    - Need prelimiary tables for:
        - **Competitions** (leagues/tournaments)
        - **Teams**
        - **Matches**
        - etc.