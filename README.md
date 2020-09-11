# demo-host-website

For demonstration purposes only. This website is used to illustrate how trust certificates are uploaded, configured and verified.


## Goal

The goal of uploading the ETH public key to the website is to lower the risk of buying a ticket from a fraudulant actor. 
By including the same ETH public key that also created the event on the Ethereum blockchain we can make sure the same entity also has access to the offial event website.

## Setup
Add a new route to your website as follows:
```
https://root-url.com/idetix
```
When performing a GET request on this route, a resonse in the followin JSON format is expected:

```json
{
  "address":"0x49A8246758F8d28e348318183d9498496074cA71"
}
```
