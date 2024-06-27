<!-- @format -->

# Google Books Search Engine

## Description

This application is a Google Books Search Engine built with the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to search for books via the Google Books API and save their favorite books to their account. The app uses GraphQL with Apollo Server for efficient data fetching and manipulation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

1. Clone the repository:

```

git clone https://github.com/jakepears/google-books-search.git

```

2. Navigate to the project directory:

```

cd google-books-search

```

3. Install dependencies for both server and client:

```

npm install
cd client
npm install
cd ..

```

4. Create a `.env` file in the root directory and add your MongoDB URI:

```

MONGODB_URI=your_mongodb_uri_here

```

5. Start the development server:

```

npm run develop

```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Use the search bar to look for books.
3. Click on "Login/Sign Up" to create an account or log in.
4. Once logged in, you can save books to your account and view them later.

## Features

- Search for books using the Google Books API
- User authentication (sign up and login)
- Save and remove books from your personal list
- Responsive design for mobile and desktop use

## Technologies Used

- MongoDB
- Express.js
- React
- Node.js
- GraphQL
- Apollo Server
- JWT for authentication
- React Bootstrap for styling
- Vite for fast development and building

## License

This project is licensed under the MIT License.
