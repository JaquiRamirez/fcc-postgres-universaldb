# fcc-postgres-universaldb
## Overview
The Universe Database is a PostgreSQL database designed to model celestial entities such as galaxies, stars, planets, moons, and black holes. It includes various attributes for each entity and establishes relationships between them.

## Database Structure
Tables
1. galaxy - Stores information about different galaxies.
2. star - Represents stars within galaxies.
3. planet - Stores planetary data, including population and star association.
4. moon - Represents moons orbiting planets.
5. blackhole - Contains details of black holes and their properties.

Relationships
- A galaxy can have multiple stars.
- A star can have multiple planets.
- A planet can have multiple moons.
- A black hole can be associated with a galaxy.

## Installation and Setup
1. Ensure you have PostgreSQL 12 installed on your system.

2. Open a terminal or command line interface and navigate to the directory where universe.sql is located.

3. Execute the database dump file using:
```sql
psql -U your_username -d your_database < universe.sql
```
Replace your_username with the PostgreSQL username and your_database with the target database name.

## Authors and Credits
This database schema was developed as part of a FreeCodeCamp project.
