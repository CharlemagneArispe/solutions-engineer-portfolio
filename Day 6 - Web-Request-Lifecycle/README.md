# Web Request Lifecycle

## Overview

Today I studied how web requests travel from a user’s browser to a server.

## Request Lifecycle

When a user enters a URL in a browser:

1. DNS resolves the domain name into an IP address.
2. A TCP connection is established between the client and server.
3. A TLS handshake occurs if HTTPS is used.
4. The browser sends an HTTP request.
5. The server processes the request.
6. The server sends an HTTP response.
7. The browser renders the webpage.

## Key Networking Concepts

DNS – translates domain names into IP addresses.

TCP – ensures reliable communication between systems.

HTTPS – encrypts communication using TLS.

Latency – the delay between sending a request and receiving a response.

## Learning Outcome

Understanding request flow is essential for debugging APIs and designing scalable systems.
