# middleware-IoT

Integration of new Nodes to customize the node-red node collection.

## Run

If you want to run the latest code from git, here's how to get started:

1. Create a link to middleware-IoT

        cd middleware-IoT
        sudo npm link

2. Clone the code:

        git clone https://github.com/node-red/node-red.git
        cd node-red

3. Link the node-red with middleware-IoT

        npm link node-red-contrib-middleware

4. Install the node-red dependencies

        npm install

5. Build the code

        npm run build

6. Run

        npm start
   or

        node red.js
