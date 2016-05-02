## Meteor Postgres Apollo Shopping Cart

## Setup Postgres Mac OSX

1. Get [http://postgresapp.com/](http://postgresapp.com/)

2. Install and run.

3. In the pg console, create and connect to the database

4. Modify the username in the [pg-connector](https://github.com/abhiaiyer91/meteor-pg-apollo-shopping-cart/blob/master/imports/data/pg-connector.js#L5)

```
CREATE DATABASE shopping;
\c shopping

```




## Start Meteor

```js
npm install

meteor
```


## Contribute
It'd be cool to see the feature set expand, and cleaned up. Have never used Sequelize professionally,
so can learn a lot from you people out there.