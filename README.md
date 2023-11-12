# Bookshelf API

Bookshelf API is a project for storing book data in a library. This project is the final submission for the "Belajar Membuat Aplikasi Back-End untuk Pemula" course on [dicoding.com](https://www.dicoding.com/), built using [Node.js](https://nodejs.org/) and [Hapi.js](https://hapi.dev/) for the backend.

## Features

- Add a new book
- View the list of books
- View book details
- Delete a book

## Prerequisites

Before getting started, make sure your system has:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)

## How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/bayu275/bookshelf-api.git
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

3. Run the application:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

   The application will run at `http://localhost:3000`.

## Endpoints

- **GET /books**: Get a list of all books.
- **GET /books/{bookId}**: Get details of a book based on ID.
- **POST /books**: Add a new book.
- **PUT /books/{bookId}**: Update book information based on ID.
- **DELETE /books/{bookId}**: Delete a book based on ID.

## Contribution

If you would like to contribute to this project, please create a pull request. We welcome contributions from developers.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
