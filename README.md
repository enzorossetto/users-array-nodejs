# Simple application with NodeJS to manage an array of users

## How to run

_I recomend you to use [Yarn](https://classic.yarnpkg.com/en/) to run the project_

- Clone the repository
- Open the repository folder and type `yarn` or `npm i` to download the dependencies
- To star run `yarn dev` or ǹpm run dev`

## HTTP methods
  
  _The base URL is **localhost:3000**. Add the path to the action you want to take after it_
  
  _Use some software like [Insomnia](https://insomnia.rest/) to execute the requests to the application_
  
- `GET /users`: list all the stored users;
- `GET /users/:index`: return the user in the given index. Change `:index` for a number;
- `POST /users`: pass the name of the user you want to add inside the request body as a JSON;
    
      Example: { "name": "Enzo" }
      
- `PUT /users/:index`: update the name of the user in the given index. Pass the name like the `POST` method as a JSON inside the request body;
- `DELETE /users/:index`: removes the user in the given index.
