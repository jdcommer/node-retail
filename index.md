## node-retail

node-retail is an action server for the Rasa retial starter pack targetting the Node.js platform.

## Run the action server

We won't be using the action server included in the starter package, but are building our own

1. yarn start:dev


## Setup the retail starter

1. checkout the retail starter pack
2. modify the endpoints.yaml, replace the existing address with the the address of your node-retail server (defaults to `localhost:3000`)
3. do NOT start the action server, we will start our own
4. start duckling
5. rasa shell
