# Song Play Anaysis _(Data Modeling)_

Define fact and dimension tables for a star schema for a particular analytic focus, and write an ETL pipeline that transfers data from files in two local directories into Postgres tables using Python and SQL.

#### Fact Table
 - songplays - records in log data associated with song plays i.e. records with page NextSong

#### Dimension Tables
- users - users in the app
- songs - songs in music database
- artists - artists in music database
- time - timestamps of records in songplays broken down into specific units

## How to Run

```sh
python create_tables.py
python etl.py
```

For exploration...
```sh
jupyter notebook etl.ipynb
```

For testing...
```sh
jupyter notebook test.ipynb
```

