# JWT Security Concepts

## Overview

Today I studied JWT (JSON Web Tokens) and how they are used for authentication and authorization.

## JWT Structure

A JWT consists of three parts:

Header  
Payload  
Signature

Example:

header.payload.signature

## Security Considerations

JWT tokens must be protected because they represent authenticated sessions.

Common security risks include:

- Token theft
- Cross-site scripting (XSS)
- Improper token storage

## Best Practices

- Use HTTPS
- Use short-lived access tokens
- Use refresh tokens
- Store tokens securely

## Learning Outcome

JWT-based authentication allows scalable stateless authentication in distributed systems.
