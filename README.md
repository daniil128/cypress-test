There are 2 ways I found to solve this problem

## 1. Cypress configuration
We can change the configuration of cypress like cypress.json. The default Command Timeout was set.

## 2. Element specific timeout
Please check the change in app_spec.js. We can set the timeout for the get('li') function to get the expected effect.
