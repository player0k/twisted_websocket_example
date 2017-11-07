Broadcasting with WebSocket
===========================

This example provides a WebSocket server that will broadcast any message it receives
to all connected WebSocket clients. Additionally, it will broadcast a "tick" message
to all connected clients every second.

Clients are provided for AutobahnJS and AutobahnPython.

Running
-------

Run the server by doing

    python server.py

and open

    http://localhost:8080/

in your browser.

To use the Python client, do

    python client.py
