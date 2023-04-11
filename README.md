# Data Slam Dunk: Python script to insert NBA and Top Tech Startups data into a PostgreSQL database

## Overview

Data Slam Dunk is a Python script that reads data from the NBA Players and Team Data and Top Tech Startups Hiring 2023 dataset, and inserts it into a PostgreSQL database in a performative way. The script follows good programming practices, creates separate schema and table for each dataset, and parses JSON data to create columns in the corresponding PostgreSQL table. The project includes tests and documentation to demonstrate the solution's functionality. 

This project was created as part of a challenge in the "desafio-1-março-2023" channel on Discord.

## Features

- Read data from multiple sources
- Store data in a PostgreSQL database using the appropriate data type
- Create separate schema and table for each dataset
- Parse JSON data to create columns in the corresponding PostgreSQL table
- Follow good programming practices
- Includes tests and documentation

## Usage

1. Clone the repository (git clone https://github.com/[username]/data-slam-dunk.git)
2. Install Poetry to manage dependencies
3. Navigate to the project directory
4. Install the project dependencies with Poetry

```poetry install```
5. Set up a PostgreSQL database with the appropriate credentials
6. Run the script

## License

This project is licensed under the [MIT License](https://github.com/jguilhermemv/data-slam-dunk/blob/main/LICENSE).

## Acknowledgments

- [NBA Players and Team Data](https://www.kaggle.com/datasets/loganlauton/nba-players-and-team-data)
- [Top Tech Startups Hiring 2023 dataset](https://www.kaggle.com/datasets/chickooo/top-tech-startups-hiring-2023?select=json_data.json)


