# Urban Routes End-to-End Testing

## Description
This project focuses on end-to-end testing for the "Urban Routes" web application, automating the taxi ordering process. The tests ensure the smooth functioning of key features, including:

- Address input
- Plan selection
- Phone number and credit card information entry

These tests are designed to simulate a user’s journey and verify that all functionalities work as expected, providing a seamless experience.

## Technologies and Techniques Used

- **JavaScript**: Used to write the test scripts, making the tests efficient and easy to read.
- **WebdriverIO**: A modern automation test framework for Node.js. WebdriverIO interacts with the browser directly via native web APIs, eliminating the need for Selenium WebDriver, while offering a smooth and reliable testing experience.
- **Node.js**: The runtime environment for executing JavaScript code outside the browser. It is used to run the test scripts in this project.

## Setup Instructions

### 1. Clone the Repository
Clone the repository from GitHub to your local environment using the following command:

```bash
git clone https://github.com/yourusername/hm08-qa-us.git
2. Install Dependencies
Navigate to the project directory and install the required dependencies using npm:

bash
Copy code
cd hm08-qa-us
npm install
3. Run the Tests
Once the dependencies are installed, you can run the end-to-end tests with the following command:

bash
Copy code
npx wdio run wdio.conf.js
This will execute the test scripts and provide a report on the results of the end-to-end tests.

