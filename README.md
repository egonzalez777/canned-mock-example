# Canned mock app example.

Before we get started, you are required to install canned using the following command:

`npm install -g canned`

Once the nodejs module has installed, go ahead and `cd` into your root folder. Finally, start the server by adding the following command:

`canned`

This will start a simple server and assign port 3000.

To access your server, use cURl or any rest client that allows you to make http requests.

Example:

`curl -XGET http://localhost:3000/users/ | python -m json.tools`

The above command will make a request and display the output in human readable text.

Thanks!
