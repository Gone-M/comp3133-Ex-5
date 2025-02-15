# Movie Management with GraphQL and Apollo Server

This project is a **Node.js + GraphQL** based movie management system that utilizes **Apollo Server** to handle queries and mutations. The application allows users to manage a list of movies with fields such as `id`, `name`, `director_name`, `production_house`, `release_date`, and `rating`.

## **Project Setup**

### **1. Clone the Repository**
I started by cloning the given template repository from GitHub:

```sh
git clone https://github.com/Gone-M/comp3133-Ex-5.git
cd w6_3133_nodejs_express_apollo_graphql
```

### **2. Install Dependencies**
I installed the required dependencies using `npm`:

```sh
npm install
```

If there were any GraphQL-related errors, I ensured the correct version was installed:

```sh
npm install graphql
```

## **Implemented Features**
### **1. GraphQL Schema**
I created a schema to define the `Movie` type and GraphQL operations (`Query` and `Mutation`).  

### **2. Queries**
- `getAllMovies`: Fetches all movies from the database.
- `getMovieById(id: ID!)`: Fetches a movie by its ID.

### **3. Mutations**
- `addMovie`: Adds a new movie to the database.
- `updateMovie`: Updates an existing movie’s details.
- `deleteMovie`: Deletes a movie by its ID.

## **Testing the API**
### **1. Start the Server**
I ran the server using:

```sh
node server.js
```
or using `nodemon` for development:

```sh
npm run dev
```
