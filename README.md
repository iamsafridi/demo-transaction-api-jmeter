# Dmoney API Testing

This repository contains JMeter test scripts for testing the Dmoney system API. The test scenario involves creating an agent and a customer, performing various financial transactions, and checking the system's response.

## Getting Started

To run the tests, you will need [Apache JMeter](https://jmeter.apache.org/) installed on your machine.

1. Clone this repository to your local machine:

2.Open Apache JMeter and load the provided JMX file located in the tests directory.

3.Adjust the test parameters such as the API endpoint, authentication details, or any other necessary configurations.

4.Run the JMeter test plan.


## Test Scenario
The test scenario covers the following positive test cases:
  1.Create an agent and a customer.
  2.Deposit 2000 tk to the agent from the system account.
  3.Deposit 1000 tk to the customer from the agent account.
  4.Check the balance from the customer account.
  5.Withdraw 500 tk from the customer account.
  6.Payment of 200 tk from the customer account to the merchant account (Merchant account: 01686606905).

## Screenshots
![screencapture-file-D-apache-jmeter-5-6-3-bin-projects-Reports-index-html-2024-02-05-17_42_33](https://github.com/iamsafridi/demo-transaction-api-jmeter/assets/82276738/2ff0d35e-2242-4c63-bc95-5c4aa65d794a)


