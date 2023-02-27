# nosql-social-network-api

## Description

A node app to route all CRUD functions for a social media website using mongoDB.

## Installation

Open the terminal in the root directory & enter the following:

* npm install
* npm start

## User Story

```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Mock Up

The following images show examples of the application's API routes being tested in Insomnia.

The following image shows GET routes to return all users being tested in Insomnia:

![Demo image of GET routes to return all users and all thoughts being tested in Insomnia.](/assets/all-users-insomnia.jpg)

The following image shows POST routes for users being tested in Insomnia:

![Demo image that shows POST routes to create a single user being tested in Insomnia.](/assets/create-user-insomnia.jpg)

The following image shows GET routes to return all thoughts being tested in Insomnia:

![Demo image of GET routes to return all thoughts being tested in Insomnia.](/assets/all-thoughts-insomnia.jpg)

The following image shows POST routes for reactions being tested in Insomnia:

![Demo image that shows POST routes to create a reaction to a thought being tested in Insomnia.](/assets/create-reaction-insomnia.jpg)


## Links

GiHub: https://github.com/arinielson/nosql-social-network-api

Video: 

## Credits

University of Utah

## License

Public