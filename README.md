# bitcoin_paper_wallet_generator

UNDER DEVELOPMENT!

This repo is for a bitcoin paper wallet generator. 

Team Members:
Matt Nutsch
Trevor Frame
Harlin Glovacki

Concept:

A Bitcoin paper wallet consists of 2 strings. A private key and a public key. The private key cannot include a zero or a capital letter O. The public key is a hash of the private key, created with the SHA256 hash. 

We will create a single page HTML/JavaScript app.

The user clicks a button to generate a new wallet.
The JavaScript will first create a random private key. 
It will then create the public key by generating a SHA256 hash of the private key.
The JavaScript will call a QR code library twice, to generate QR code images for each key.
Finally, the private and public keys will be rendered the HTML page, along with their corresponding QR code images.
