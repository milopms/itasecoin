<h1 align="center">
Itasecoin [ITASE, ŧ]  
<br/><br/>
<img src="https://cdn.discordapp.com/attachments/485464301516095509/931659437830205440/itasecoin.png" alt="Itasecoin" width="300"/>
</h1>

<div align="center">

Copyright (c) 2009-2022 Bitcoin Developers<br>
Copyright (c) 2011-2022 Litecoin Developers<br>
Copyright (c) 2022 Milovan PMS

</div>

Itasecoin is a cryptocurrency originally created for high school and college students in France. It is a very lite version of Litecoin, using the Scrypt hashing method as a proof-of-work algorithm. <br>The Itasecore software allows anyone in the whole world to operate a node in the Itasecoin blockchain networks. It is adapted from Litecoin Core and other cryptocurrencies.
 - 1 minute block targets
 - subsidy halves in 630k blocks
 - 63 million total coins
 - 50 coins per block

For more infomation, see [itasecoin.com](https://itasecoin.com)

## Usage

To get started with Itasecore, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Itasecore is self-documenting and can be browsed with `itasecore-cli help`, while detailed information for each command can be viewed with `itasecore-cli help <command>`. 
<br>Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Ports

Itasecore by default uses port `25075` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `29045` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   25075 |   19107 |   13107 |
| RPC      |   29045 |   12038 |   29074 |

## Ongoing development

Itasecore is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software. (even you!)

Main development resources:

* [Github Projects](https://github.com/milopms/itasecoin/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [Github Discussion](https://github.com/milopms/itasecoin/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the Itasecore software, the underlying protocols and the ITASE asset.  

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

## Contributing

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/milopms/itasecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Itasecore. There are often
[topics seeking help](https://github.com/milopms/itasecoin/labels/help%20wanted)
where your contributions will have high impact and get very appreciation.

## Communities

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the lastest meme, learn
about Itasecoin, give or ask for help, to share your project.

Here are some places to visit:

* [Discord](https://discord.gg/M86FaRchGb)
* [Itasecoin Twitter](https://twitter.com/itasecoin)
* [Itasecoin Instagram](https://instagram.com/itasecoin)
* [Itasecoin Reddit](https://reddit.com/r/itasecoin)

## Frequently Asked Questions 

Do you have a question about Itasecore? Your answer may be in the
[FAQ](https://itasecoin.com/faq) or the
[Q&A section](https://github.com/milopms/itasecoin/discussions/categories/q-a)
of the discussion board!

## License
Itasecore is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
