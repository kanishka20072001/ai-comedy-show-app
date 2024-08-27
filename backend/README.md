# AI Comedy Show Backend

This is the backend server for the AI Comedy Show application. It uses Express, MongoDB, and the OpenAI API to generate and store comedy shows.

## Getting Started

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Create a `.env` file and add your OpenAI API key as shown in `.env.example`.
4. Run `npm install` to install dependencies.
5. Run `npm start` to start the server.

## API Endpoints

- **POST /generate-comedy**: Generates a comedy show based on the provided style and voice.

## Dependencies

- **Express**: Web framework for Node.js.
- **Mongoose**: MongoDB object modeling tool.
- **OpenAI**: API client for OpenAI.

## Project Structure

- **server/server.js**: Main server file with routes and database configuration.
- **.env**: Environment variables (e.g., API keys).
- **.gitignore**: Specifies files to ignore in Git.
- **package.json**: Project metadata and dependencies.
