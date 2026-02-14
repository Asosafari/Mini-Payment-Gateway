# Mini-Payment-Gateway
The store can record payments through our API.

## Overview

The API allows:

- Creating a payment request
- Retrieving payment status by ID
- Listing all payments for a user

## Payment Lifecycle
PENDING → SUCCESS | FAILED | EXPIRED


## Business Rules

- `amount` must be positive
- `currency` is required
- `paymentId` must be unique (UUID)
- Only authorized users can access the endpoints

