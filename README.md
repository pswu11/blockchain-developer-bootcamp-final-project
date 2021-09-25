# An Universal API Payment Service

An experimental project of an open source payment gateway for developers to get access to various API services and pay with tokens, instead of using centralized payment services such as Stripe. 

## Example User Flow - Developer

- A developer (user) can buy ERC-20 tokens that works for several different API services via services such as Uniswap. 

- Users can grant approvals to API services that they're using regularly with an allowance.

- Whether the API is charged per request or per time used, they can charge based on users' allowance. 


## Example User Flow - API Provider

- API providers can create their own services to send transactions to smart contract. So the whole payment process doesn't rely on any centralized payment providers.

- Alternatively, API providers can choose to use trust-worthy middleware (also an API service) to bundle the transactions without building their own services. 
