# Twitter Clone on Nuxt.js

This is a Twitter clone built using the Nuxt.js framework and powered by Prisma for database connectivity. It includes features such as posting tweets, liking and commenting on tweets, and following other users.

## Installation

To get started, clone this repository to your local machine:

```
git clone https://github.com/div4211111/vue-twitter-clone.git
```

Next, navigate to the project directory and install the necessary dependencies:

```
cd vue-twitter-clone
npm install
```

## Configuration

Copy the `.env.example` file to `.env`:

```
cp .env.example .env
```

By default, the application uses MongoDB as the database. If you want to use a different database, you can modify the database URL in the `.env` file.

The application also requires a Twitter API key to function properly. You can obtain your own key by creating a new app on the Twitter Developer Portal and adding your API key and secret to the `.env` file.

## Running the Application

To run the application in development mode, use the following command:

```
npm run dev
```

This will start the development server at `http://localhost:3000`.

To run the application in production mode, use the following command:

```
npm run build
npm run start
```

This will build the application and start the server at `http://localhost:3000`.

## Testing

To run the unit tests, use the following command:

```
npm run test
```

This will run all of the unit tests in the `tests/unit` directory.

## Contributing

Contributions are always welcome! If you find a bug or have an idea for a new feature, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
