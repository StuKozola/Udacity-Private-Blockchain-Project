# Private Blockchain Application

This repository contains the solution for Udacity's Blockchain Developer Nanodegree project "Creating your own private block chain".  The application is to build a private blockchain for the purpose of registering stars.  The details of the project can be found in the [project description](Project_README.md).  

## Installation and Running

To run the application, download the files to a local directory.  From inside the directory, install the necessary node.js packages:

```bash
npm install
```

To start the server:

```bash
node app.js
```

The application is will be available on http://localhost:8000

## Testing
Testing can be performed using `curl` or Postman.  Shown below are the steps for testing the applciation with Postman using the test cases in the [Postman collection](udacity-private-blockchain-project.postman_collection.json)

Step 1: Create/test the genesis block

![Genesis Block](screenshots/genesis.png)

Step 2: Request ownership by submitting a wallet address

![Submit Address](screenshots/validate.png)

Step 3: Sign the address in your wallet
This example shows how to sign the message using [Bitcoin Core](https://bitcoin.org/en/download).  Other wallets may be used in it's place.

![Sign message](screenshots/sign_message.png)

Step 4: Submit a star

![Submit star](screenshots/star_submission.png)

Step 5: Retrieve listing of stars by owner

![Retrieve list of stars by owner](screenshots/retrieve_stars.png)

Step 6: Validate the blockchain of stars

![Validate the chain](screenshots/validateChain.png)