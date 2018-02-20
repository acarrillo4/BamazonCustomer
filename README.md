# [BamazonCustomer](https://github.com/acarrillo4/BamazonCustomer)
###### Amazon-like storefront using MySQL and Node.js

## Requirements
1. Node.js
1. MySQL

## Installation
###### Clone this repository from GitHub
`$ git clone <repo>`
  
###### Navigate to directory on your local machine and install npm dependencies
`$ npm install`

## Connect to localhost using:
* Sequel Pro (Mac)
* MySQL Workbech (PC)

###### Run bamazon.sql to initialize database and create necessary schemas
###### Data can be imported from bamazonData.sql

## Customer Actions
###### Using your bash terminal, run bamazonCustomer.js from within the cloned directory
`$ node bamazonCustomer.js`

###### Follow the on-screen prompts to place an order
* If there is enough inventory, you'll be provided a total.  
  1. The SQL database gets updated accordingly on backend
  1. You'll then have the option to continue shopping (start over) or close your session
###### [Example Video - Processed Order & Continue Shopping](https://www.screencast.com/t/2MQPzb3INA98)
* If there isn't enough inventory to complete your order, you will be notified.
    1. You'll then have the option to continue shopping (start over) or close your session
*  Once user chooses not to continue shopping, they're provided with the updated MYSQL table
###### [Example Video - Insufficient Inventory & Done Shopping](https://www.screencast.com/t/SeIFw2aNhja)
