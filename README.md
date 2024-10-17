# StockWatch

# <h1> Trending Stocks App </h1>
The Trending Stocks App is a web application developed using Flask that leverages the Indian Stock Exchange API from RapidAPI. It offers real-time data on trending stocks, highlighting top gainers and losers, and allows users to access historical data for specific stocks over the past month.

# <h3> What is RapidAPI? </h3>
RapidAPI is a platform that connects developers with thousands of APIs, making it easy to discover and integrate various services. This application utilizes the Indian Stock Exchange API available through RapidAPI, ensuring smooth data retrieval for both real-time and historical stock market information.

Key Features
Displays real-time trending stocks, including top gainers and losers.
Provides a detailed view of historical stock data over the last month for selected stocks.
Clean, user-friendly interface with a card-based layout for easy navigation.
Getting Started
Option 1: Using Docker
Running the app with Docker is straightforward. The Docker image is hosted on Docker Hub, and you can quickly get started with the following steps:

<h2> Pull the Docker image: </h2>

```
docker pull tamannabothra/stockwatch
```
<h2> Start the Docker container:</h2>

```
docker run -p 5000:5000 tamannabothra/stockwatch
```

Open the app by visiting http://localhost:5000 in your browser.

Option 2: Running Locally
<h2> Clone the repository to your local machine: </h2>

```
https://github.com/tamannabothra/StockWatch.git
```

<h2> Install the necessary dependencies: </h2>

```
pip install -r requirements.txt
```
Replace the api_key in the code with your RapidAPI key.

Run the application:

Access the app at http://localhost:5000.

Technology Stack
Flask for backend development.
HTML & CSS for building the frontend interface.
Requests library to make API calls.
API Integration
The application connects with the Indian Stock Exchange API via RapidAPI to fetch real-time stock data as well as historical data, providing users with comprehensive market insights.
