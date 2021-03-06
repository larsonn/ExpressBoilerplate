<p align="center">
  <img src="https://github.com/aichholzer/ExpressBoilerplate/raw/master/assets/boilerplate.png" alt="Express boilerplate" width="600" />
</p>
<p>&nbsp;</p>

An [Express](https://github.com/expressjs/express) application ready to use -and extend- in seconds!

This is a basic setup and it's intended for making the initial application architecture process much
faster and easier.


#### Setup

1. Make you have access to MongoDB (local or remote, does not matter),
2. clone this repository,
3. install what's needed: `npm i`,
4. copy `.env.sample` to `.env` (change the values, if needed),
5. compile the static assets (these are located in `/source`): `npm run build`,
6. run the application: `npm start`


#### Done

Visit [http://localhost:9000](http://localhost:9000) (Unless you changed the port in your `.env` file)


#### Practice

* Take a look at `/app/core/controllers/cities.js` and `/app/core/controllers/users.js`, they both implement some basic CRUD logic.
* Create forms in their respective views (`/app/core/views/`) that allow you to create `users` and `cities`.
* Implement `delete` methods for both entities.
* Submit a pull request.

*Happy learning.*


#### Contribute
```
fork https://github.com/aichholzer/ExpressBoilerplate/
```


#### License

[MIT](https://github.com/aichholzer/ExpressBoilerplate/blob/master/LICENSE)
