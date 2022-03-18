# Private Blockchain Application
An application that allows people to register stars, and track the ownership of each stars.

## Testing the application functionalities

1. Run your application using the command `node app.js`
You should see in your terminal a message indicating that the server is listening in port 8000:
> Server Listening for port: 8000

2. To make sure your application is working fine and it creates the Genesis Block you can use POSTMAN to request the Genesis block:
    ![Request: http://localhost:8000/block/0 ](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Get%20Genesis%20Block%20-%20GET.png)
3. Make your first request of ownership sending your wallet address:
    ![Request: http://localhost:8000/requestValidation ](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Request%20Ownership%20-%20POST.png)
4. Sign the message with your Wallet:
    ![Use the Wallet to sign a message](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Sign%20message.png)
5. Submit your Star
     ![Request: http://localhost:8000/submitstar](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Submit%20Star%20-%20POST.png)
6. Retrieve Stars owned by me
    ![Request: http://localhost:8000/blocks/<WALLET_ADDRESS>](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Retrieve%20stars%20by%20own%20address%20-%20GET.png)
7. Validate Chain
    ![Request: http://localhost:8000/validateChain](https://github.com/Harjacober/PrivateBlockchain/blob/main/Postman-screenshots/Validate%20Chain%20-%20GET.png)
