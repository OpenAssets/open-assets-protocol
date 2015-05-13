# Open Assets Protocol

The Open Assets Protocol is a simple and powerful protocol built on top of the Bitcoin Blockchain. It allows issuance and transfer of user-created assets. The Open Assets Protocol is an evolution of the concept of colored coins.

The following documents are available:

* [Open Assets Protocol specification](specification.mediawiki): Specification of the core protocol
* [Open Assets Address Format specification](address-format.mediawiki): Special address format for wallets supporting the Open Assets Protocol, preventing assets from being sent to legacy wallets
* [Asset Definition Protocol specification](asset-definition-protocol.mediawiki): A protocol built on top of the Open Assets Protocol for associating an asset with metadata
* [Payment Requests specification](payment-requests.mediawiki): extensions to [BIP-70](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) and [BIP-21](https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki) describing payments in terms of assets instead of (or together with) regular bitcoins

Source code related to the Open Assets Protocol:

* [`openassets` Python module](https://github.com/OpenAssets/openassets): The reference implementation of the Open Assets Protocol
* [Colorcore](https://github.com/OpenAssets/colorcore): A client providing a command line and RPC interface for performing operations through the Open Assets Protocol
* [NBitcoin](https://github.com/NicolasDorier/NBitcoin): A Complete .NET Library for Bitcoin with its [TransactionBuilder](http://www.codeproject.com/Articles/835098/NBitcoin-Build-Them-All) to issue, transfer and swap assets
