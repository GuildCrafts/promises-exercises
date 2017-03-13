## PG-PROMISE-EXERCISES
Exercises which tickles your JavaScript Promises knowledge.

## Getting Started

#### 1. Create and load the database
Run the following commands in a terminal window
```bash
createdb pg-promise-exercises
psql -d pg-promise-exercises -f schema.sql
```

#### 2. Fix `user` in the `postgresConfig` in  `exercises.js` to your username so that you can connect to your the postgres database
Your username can be found by running this in a terminal window
```bash
whoami
```

## Exercises

Complete all the exercises 1 - 7 in `exercises.js` by carefully reading the instructions listed.

Constantly check if your functions and assertions work by running this in a terminal window
```bash
node exercises.js
```
