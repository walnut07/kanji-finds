# Kanjify
## About the project
<img width="1280" alt="スクリーンショット 2022-08-05 10 02 24" src="https://user-images.githubusercontent.com/90857923/182979879-f386406e-e7e5-4734-a76c-4656859b9291.png">

Want to know how to spell your name in kanji? 
Kanjify is here for you to give you a kanjified name.

Try it out here: https://kanjify.herokuapp.com

### Built with
* [React](https://reactjs.org/)
* [Express](https://expressjs.com/)
* [Knex.js](http://knexjs.org/)
* [PostgresSQL](https://www.postgresql.org/)
* [Heroku](https://www.heroku.com/)
* [Kanji Alive API](https://app.kanjialive.com/api/docs)
* [WanaKana](https://github.com/WaniKani/WanaKana)

## Getting Started
Once forking this repository and cloning it to your computer, install libraries.
- npm

In `Kanjify/server` and `Kanjify/client`, run
```shell
$ npm install
```

- Express / Knex.js / Wanakana

In `Kanjify/server`, run
```shell
$ npm install express knex wanakana
```

Then, set up your local database.
- PostgreSQL

In psql,
```sql
CREATE DATABASE kanjify;
\c kanjify
CREATE TABLE kanji;
```

In `Kanjify/server/db`, create `.env.local` file. Write information below.

In `Kanjify/ser 

After installing those libraries, you should be able to run the app.
In `Kanjify/client` and `In Kanjify/server`, run
```shell
$ npm start
```

## Logic behind the scenes
This map shows how frontend and backend communicate each other. It is not 100% accurate but was made for improving developers' understanding.
![Map describing the kanjifying process](https://user-images.githubusercontent.com/90857923/182984379-71b84db5-31c3-4c62-8c94-cb71d4ce338f.jpg)

