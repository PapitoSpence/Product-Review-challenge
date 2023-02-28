# Product-Review-challenge
This is an e-commerce application that allows users to leave reviews for products.

# Domain Modeling
For this app, we have three models, as follows:
<ul>
    <li>User</li>
    <li>Product</li>
    <li>Review</li>
In our domain, we have:

    A Product that has many Users through Reviews.
    A User that has many Products through Reviews.
    A Review that belongs to a User and a Product.
    
    
       </ul>
    
    
# Entity Relationship Diagram
We can represent our domain model using the following Entity Relationship Diagram:
ERD
Requirements
    Ruby version: 3.0.2
    
# Installation
    Clone this repository to your local machine.
    Install dependencies: bundle install.
    Create the database: rails db:create.
    Run database migrations: rails db:migrate.
    Seed the database: rails db:seed.
    Run the console: rake console.
    create migration
    
# Development
After checking out the repository, run `bundle install` to install dependencies. Then, run `rake console` to run the tests.

## Contributing
If you would like to contribute to this project, feel free to submit a pull request.

## License
The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

# Authors
Spencer Mwenda
