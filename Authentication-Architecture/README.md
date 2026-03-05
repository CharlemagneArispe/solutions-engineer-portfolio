# Authentication System Architecture

## Overview

Today I designed an authentication system architecture using JWT and OAuth concepts.

Authentication systems verify the identity of users before granting access to protected resources.

## Authentication vs Authorization

Authentication verifies the identity of a user.

Authorization determines what actions the authenticated user is allowed to perform.

## Authentication Flow

1. User submits login credentials.
2. Authentication server verifies credentials.
3. System generates a JWT token.
4. The token is returned to the client.
5. Client includes the token in future requests.

## OAuth Integration

Users can also authenticate through third-party providers such as:

- Google
- Facebook
- GitHub

This is commonly known as OAuth login.

## Learning Outcome

Understanding authentication flows is essential for building secure applications.
