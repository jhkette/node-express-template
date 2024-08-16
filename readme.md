# DevCamper API

This is from a udemy course by Brad Traversy.
It serves as a useful template for a well designed node/express API
It has
- Clearly defined routes
- The routes call functions in controller files which are clear and easy to read
- Authentication handled with JSON web tokens
- Clear error handling using a custom error handler middleware
- Adheres to security best practices

## Usage

Rename "config/config.env.env" to "config/config.env" and update the values/settings to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```

## Demo

Extensive documentation with examples [here](https://documenter.getpostman.com/view/8923145/SVtVVTzd?version=latest)

- Version: 1.0.0
- License: MIT
- Author: Brad Traversy
