This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Make sure to run the server before

Run the server before this client app, then npm `npm start` will ask if you want to use another PORT while another app is using port 3000. It is because we set the server to listen to port 3000 (Hardcode), and the client is fetching localhost:3000 to get respons from the server.
