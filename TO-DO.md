# To Do List for Project
1/4/26: still working on scrapinf data from FBref, looking into StatsBomb (data provider/company behind FBref) and their API/python package statsbombpy. In the meantime pull data they have available from their opendata git repository

- pipe JSON data into DuckDB database
    - Need prelimiary tables for:
        - **Competitions** (leagues/tournaments)
        - **Teams**
        - **Matches**
        - etc.
        **Above should be started, need to start cleaning data**
        - look into fixing events table in DuckDB

- Look in worldfotballr R package for pulling fbref data
