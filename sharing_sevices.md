Sharing Services
======================

## Resources for researching
* [similartech](https://www.similartech.com)
* [financesonline](https://financesonline.com/)

## Features for service
* Login with Facebook, google,...
* Manage Account of users (Profile, service of user, level of user)
* Explore services
* Report trend
* Machine learning
* Geo Location, Map
* Verify service of user
* Offline Feature
* Manage price range
* Rating for user service
* Video, voice call transaction management
* Payment
* Q&A
* Realtime

## The open source software for backend
* [BaasBox](http://www.baasbox.com/en/)
* [Loopback]

### Good reads
* [A Full List of the Best Frameworks for Building Android Apps](https://yalantis.com/blog/list-of-best-frameworks-for-android-app-development/)

## Payment Technology 3rd Party
### Tools
* [Adyen](https://www.adyen.com/)
* [Braintree](https://www.braintreepayments.com/)

![Braintree payment framework](https://developers.braintreepayments.com/img/developers/diagram-client-perspective.png)

__How Braintree Works__
Braintree offers complementary client and server SDKs. They represent the Client-side Encryption solution that combines the best of Braintree’s traditional Server-to-Server (S2S) approach and the innovative Transparent Redirect (TR) solution. In a nutshell, the Braintree mechanism can be described as following:

1. The application backend generates a client token using the Ruby SDK for the frontend that initializes the JavaScript SDK using that client token.
2. The Braintree-provided JavaScript library encrypts sensitive data using the public key and communicates with Braintree before the form is ever posted to your server.
3. Once the data reaches Braintree’s servers, it is decrypted using the keypair’s private key, then returns a payment method nonce to your client code. Your code relays this nonce to your server.
4. Your server-side code provides the payment method nonce to the Ruby SDK to perform Braintree operations.
 


* [Stripe](https://stripe.com/)

### Good reads
* [Compare Braintree vs. Adyen](https://comparisons.financesonline.com/adyen-vs-braintree)
* [adyen-vs-braintree](https://www.similartech.com/compare/adyen-vs-braintree)
* [adyen-vs-stripe](https://www.similartech.com/compare/adyen-vs-stripe)

## Video Call 3rd Party
### [Sinch](https://www.sinch.com/)

![Model-intergrate-sinch-to-backend](https://download.sinch.com/docs/javascript/latest/user-guide/images/authentication_papi_partner.png)


### [Quickblox]()
### [Tokbox]()
### Good reads

