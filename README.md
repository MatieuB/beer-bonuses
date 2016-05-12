# Beer Bonuses

Installation:

```sh
createdb beer-bonuses
npm install
cp .env.example .env # and change that file if you need to...
knex migrate:latest
```

PROTIPS:

* Are you worried about a Syntax error on migrations or seeds? Any Syntax errors will show up when you run:

  ```sh
  node migrations/20160512103011_create-users.js
  ```

* `Error: There is no pool defined on the current client` - something is wrong with the connection to postgresql
