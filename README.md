Florkestra Web Socket Relay Server
==================================

This project provides the basic scaffolding for a Node.js-based application that will:
* Serve static web resources from the <code>web</code> directory using Express
* Listen for Web Socket connections on port 8081
* Relay incoming messages from a Web Socket client to all other connected clients

How To Use It
-------------

0. Fork and clone this repository
1. Place all your web resources (i.e. scripts, HTML pages, style sheets, etc.) in the <code>web</code> directory
2. Install all dependencies by running <code>npm install</code>
3. Start the relay server by running <code>node .</code>
4. Access your HTML pages from a web browser at <code>http://localhost:8081</code>
5. Write your own custom code to connect to the relay server using a Web Socket connection at <code>ws://localhost:8081</code>
6. Send messages messages to the server using your Web Socket; they'll be relayed to all other connected clients
