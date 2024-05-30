The project is a Real-Time Auction Platform developed using Node.js Express.js and MongoDB database for storing details where users can browse different categories of products, view ongoing auctions, bid on items, and manage their accounts. The platform also allows sellers to list their products for auction.

Step 1: Create the project folder using the following command.
mkdir auction-platform
cd auction-platform

Step 2: Create a new project directory and navigate to your project directory.
mkdir server
cd server

Step 3: Run the following command to initialize a new NodeJS project.
npm init -y

Step 4: Install the required the packages in your server using the following command.
npm install express body-parser cors mongoose

Step 5: Start the Server
In the terminal, navigate to the server folder and run the following command to start the server:
node index.js

Step 6: Go to root directory and create the React application using the following command.
npx create-react-app client
cd client

Step 7: Install the required packages in your application using the following command.
npm i react-router-dom axios styled-components
