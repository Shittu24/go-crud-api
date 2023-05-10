# CRUD API With GO

## Introduction

This is a simple CRUD API built with Go without any database where you can create, delete, update and get a information about a movie.

##### Do the stuff below to initialize your project

1. Clone the repository
   `git clone https://github.com/Shittu24/go-crud-api.git`
2. Change the directory
   `cd go-crud-api`
3. Get all the dependencies
   `go mod tidy`
4. Run your project
   `go run main.go`

5. After you've built the project, these are the queries to interact with the API on Postman -

#### Get All Movies

To get all movies information - http://localhost:9000/movies  GET Request

#### Get Specific Movie

To get a particular movie information - http://localhost:9000/movies/:id  GET Request

#### Create Movie

To create a new movie information - http://localhost:9000/movies/   POST Request Request

#### Delete Movie

To delete a particular movie information - http://localhost:9000/movies/:id   DELETE Request

#### Update Movie

To update a particular movie information - http://localhost:9000/movies/:id   PUT Request
