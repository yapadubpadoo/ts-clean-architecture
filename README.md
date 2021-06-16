# ts-clean-architecture

Let's say we have to a payment service to support our E-Marketplace website.

The core business logics as the following:

1. The payment service will use the following information in order to make a payment
   - Pay Amount
   - Source of Money
2. User can pay to the marketplace using any Bank API.
3. User can pay to the marketplace using any Credit Card.
4. User can pay to the marketplace using Internal Wallet.

We'll try to implement this system in the Clean Architecture way.
