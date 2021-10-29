# E-Commerce Backend (ORM)

The goal of this project was to create a back-end for an e-commerce site. This was accomplished using Express.JS, Sequelize, MySQL. This applications utilizes mySQL to create the database models and associations then demonstrates the API Routes performing RESTful CRUD operations as displayed in the walk through videos below.

* [MySql DB and Seeds set up](https://watch.screencastify.com/v/myQEfl6qDdhhtSqAB83Y)
* [Insomnia Tests on GET, POST, PUT, DELETE](https://watch.screencastify.com/v/OIgbEc2MMKUjeqUJh47t)

## Installation

The user will need to clone the repository from GitHub and `npm install`  Node.js, Express.js, and Sequelize. Once downloaded, open the terminal and run `mysql -u root -p` and enter the password listed in the .env file. Then source the schema.sql using the command `source db/schema.sql` and then exit mysql and source the seed data by entering the command `node seeds/index.js`. Finally, connect to the server to test by utilizing the command `node server.js`.

## Usage

This application allows the user to view, add, edit and delete any category, product, or tags.

## Authors

* **Matt Weichel** 

- [Link to Portfolio Site](https://maweiche.github.io/pro_portfolio/)
- [Link to Github](https://github.com/maweiche)
- [Link to LinkedIn](www.linkedin.com/in/mattweichel)

## License

This project is licensed under the MIT License 

## Acknowledgments

* Hat tip to anyone whose code, libraries, packages, or UI was used  / inspired from
