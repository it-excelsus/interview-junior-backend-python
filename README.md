# interview-junior-backend-python

Dear Applicant,

Thank you once again for apply for the Junior Backend Developer position at it-excelsus GmbH. With the following task, we would like to assess your coding skills. The expected timeline for this assigment is **one week**.

Below, you will find two folders. The [`backend`](./backend) Folder contains a basic FastAPI application. To start the application please run `./start_server.sh`

# What is the task?

Implement a backend API for an automated trading system. Include endpoints for placing trades, monitoring market data, and managing trading trategies. Integrate with financial market APIs for real-time data.

1. Market Data Integration:
    - Integrate with a financial market API to fetch real-time market data.
    - Create API endpoints to retrieve live market prices, historical data, and other relevant information.

2. Place Trades Endpoint:
    - Develop an API endpoint for placing trades.
    - Support various order types (market orders, limit orders, stop orders) and validate user input.

3. Monitor Portfolio and Positions:
    - Create endpoints for users to view their current portfolio holdings and open positions.
    - Implement features for calculating account balance, equity, and unrealized gains/losses.

4. Trading Strategy Management:
    - Implement an API for managing trading strategies.
    - Allow users to create, modify, and deactivate trading strategies based on technical indicators, moving averages, etc.

5. Real-time Market Data Streaming:
    - Implement WebSocket support for real-time streaming of market data.
    - Allow users to subscribe to live price updates and receive notifications.

6. Historical Trade Data:
    - Create API endpoints for retrieving historical trade data for a specific user or instrument.
    - Enable users to analyze their past trading activities.

7. Risk Management:
    - Implement risk management features, such as setting stop-loss and take-profit levels for trades.
    - Provide alerts or notifications when risk thresholds are reached.

8. Transaction History and Reporting:
    - Develop endpoints for retrieving a user's transaction history.
    - Enable users to generate reports summarizing their trading activities.

9. Security Measures:
    - Implement security measures to protect sensitive data and ensure the integrity of transactions.
    - Consider measures such as encryption, secure connections, and handling API keys securely.

10. Documentation:
    - Provide comprehensive documentation for the API, including detailed descriptions of endpoints, request/response formats, and usage examples.

11. Testing and Validation:
    - Develop and run unit tests to ensure the correctness of each endpoint.
    - Perform integration testing to verify the interactions between different components.

# How to install the enviroment and Run the Application

1. Install Anaconda/Miniconda on your system
2. Create the Enviroment given with ```conda env create -f environment.yml```
3. Execute `start_server.sh`


## Tips

- Ensure that your code is functional.
- Handle potential edge cases.
- Strive for a solution you are satisfied with.
- Interested in testing? This could be an excellent opportunity to learn!
- Keep track of your progress through git commits.

## Are you finished?

Please include 

You can submit the completed assignment in either of two ways:

1. **GitHub Repository:** Fork our repository, complete the task, and send us the link to your GitHub repository.
2. **Archive Submission:** Pack the directories into an archive, and send it to us via [email](mailto:recruiting@it-excelsus.de).

## Need assistance?

For additional help, please refer to the documentation:
- For FastAPI, consult the [FastAPI docs](https://fastapi.tiangolo.com/) page.
- For Python, consult the [Python docs](https://docs.python.org/3/) page.
- Feel free to contact us at any point. 

We look forward to reviewing your submission.

Best regards,

it-excelsus GmbH