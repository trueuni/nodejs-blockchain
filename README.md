# Blockchain project with NodeJS & Express

In this project, I have created a blockchain-like data structure with Express, NodeJS and JavaScript, that mimics how the Bitcoin blockchain works. This project has taught me how a blockchain works, how transactions are created and stored inside blocks and how these blocks get mined by nodes in a decentralised network.

## Running locally

1. Clone the project on your local device.

2. Install the dependencies using the follow command:

   ```
   npm install
   ```

3. There are 5 commands to run for starting up to 5 blockchain nodes simultaneously (you will need up to 5 separate terminal windows for this):

   ```
   npm run node_{id}, where id=1,2,3,4,5
   ```

4. You can view the blockchain structure at `localhost:300{id}/blockchain`. I recommend getting the JSON-formatter Chrome extension so you can view the data formatted. I have posted the link for this extension in the `Useful links` section.

5. To run the unit tests that have been written with Chai & Mocha for the blockchain, run the following command:

   ```
   npm run test
   ```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

