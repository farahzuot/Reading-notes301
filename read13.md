# Sending form data

#### Client/server architecture : a client (usually a web browser) sends a request to a server, using the HTTP protocol. The server answers the request using the same protocol.

![see](https://developer.mozilla.org/files/4291/client-server.png)

#### <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button.

#### action attribute defines where the data gets sent.

#### method attribute defines how data is sent.

#### GET method is the method used by the browser to ask the server to send back a given resource.

#### POST method is a the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request.

### HTTP requests are never displayed to the user, so you need to use a too like the network tap from the inspect.

![see](https://mdn.mozillademos.org/files/14691/network-monitor.png)


### retrieving the data

#### PHP offers some global objects to access the data. Assuming you've used the POST method, the following example just takes the data and displays it to the user. "Same thing for python"

#### special case: sending files : Content-Type HTTP header included in the request generated when the form is submitted.

