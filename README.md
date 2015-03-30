#Go Code Colorado 2015

http://gocode.colorado.gov/

#Overview

We cannot wait to meet everyone and geek out on Colorado open data at the Go Code Colorado events.  Because we specialize in the technologies that focus within the payments industry, Mercury is here for you both as a payments coding resource and as a fellow innovator in the open data movement.  If you want to add a convenient payment component to your product, this repo provides you with a quick start to integrating to Mercury APIs.

#APIs

* HostedCheckout&trade; -- use this API if you want to accept payments by redirecting to Mercury's servers to accept the card data.  Integrators use this API for secure payments processing on their ecommerce web sites, to remain out of payment application data security scope, and to lesson the additional compliance effort of adhering to PCI&copy; security standards.
* MobileWallets&trade; -- this API allows you to process transactions using PayPal&copy; Mobile In-Store Checkin.  A consumer will check-in to a merchant location using the PayPal mobile app and then our API allows you to get a list of consumers currently checked in at a merchant's location and process a payment for that consumer.  The cool thing about this API is that it allows merchants to accept PayPal transactions on the same MerchantID as the other card brands, merchants are funded in the same deposit as other card brands, and receive one statement.
* REST -- this is a "RESTful" transmission mechanism but sometimes integrators are more familiar with REST based API access than other types of access.  This API is typically used when an integrator integrates directly to peripheral devices and needs a way to send the clear text (or encrypted data).  There is a large conversation around security and compliance if/when your product goes into production but we can walk you through that during the challenge weekend.  REST provides access to all of our Credit, Debit, EBT, PrePaid, etc. processing functionality.
* SOAP -- ditto everything mentioned above for REST except with SOAP you will build a SoapEnvelope around a core transaction payload and then send to our endpoint.  However, the actual processing functionality that you will have access to are the same.

#Contact

If you have any questions/comments leading up to the event please contact us using the contact information here:  http://developer.mercurypay.com/support-2/.

#Samples in this repo

We use cURL to facilitate transaction processing in this repo as it is a simple utility and easily installed (if not installed by default).  But have a look around at our sample code and you will start to see an infinite number of ways to send transactions to the Mercury platform.

####©2015 Mercury Payment Systems, LLC - all rights reserved.

Disclaimer: This software and all specifications and documentation contained herein or provided to you hereunder (the "Software") are provided free of charge strictly on an "AS IS" basis. No representations or warranties are expressed or implied, including, but not limited to, warranties of suitability, quality, merchantability, or fitness for a particular purpose (irrespective of any course of dealing, custom or usage of trade), and all such warranties are expressly and specifically disclaimed. Mercury Payment Systems shall have no liability or responsibility to you nor any other person or entity with respect to any liability, loss, or damage, including lost profits whether foreseeable or not, or other obligation for any cause whatsoever, caused or alleged to be caused directly or indirectly by the Software. Use of the Software signifies agreement with this disclaimer notice.

![Analytics](https://ga-beacon.appspot.com/UA-60858025-34/GoCodeCo2015/readme?pixel)
