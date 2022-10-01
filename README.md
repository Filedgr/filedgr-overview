# filedgr-overview
This repository includes links to different Filedgr repositories. Please note that several of the project may not have a commit history in the last months we moved away from Github in favor of Gitlab for the more powerful CI/CD (in our opinion).

## XRPL CLI
__This part of project will stay open source, in the scope of our project we opted for a CLI, for the moment, in order to simply call the function via exec from various programming languages. It also simplifies the setup of our containers with the Gitlab Pypi server. We will also provide a customer facing API based on the CLI Tool.__
We use the Ripple CLI to:
- create wallets
- set trustlines
- issue NFTs, custom tokens with 0.000001 quantity, while waiting for the actual NFT in the mainnet, the memo points to a website hosted on our private IPFS
- issue Transactions tokens: tokens the NFT website is going to check, they contain the lifecycle updates, in the memo

[https://github.com/Filedgr/filedgr-ripple-cli](https://github.com/Filedgr/filedgr-ripple-cli)

__We are already aware that we should rename this and replace ripple with xrpl, we were told so.__ :-)

## The first smart NFT Template

The Vue code for our first smart NFT code is hosted below. The repo contains two versions, one protected by a OpenID login.
[https://github.com/Filedgr/filedgr-web-nft-bp/blob/master/README.md](https://github.com/Filedgr/filedgr-web-nft-bp/blob/master/README.md)

The example is given here behind this shorturl (less for tracking purposes, but the URLs are very long in our landing page, with the ipfs CID and XRPL transaction hash.

__You can login via XUMM via an arbitrery wallet__
[https://bit.ly/3f6aw9c](https://bit.ly/3f6aw9c)

## The second smart NFT Template

This template is adapted for a mobile use, and is the one going live this autumn with the precious metal recycling and circular sneakers.

[https://github.com/Filedgr/filedgr-smartnft-template](https://github.com/Filedgr/filedgr-smartnft-template)

The examples are shown here:
[https://bit.ly/3R8vnGa](https://bit.ly/3R8vnGa)
[https://bit.ly/3C242Bo](https://bit.ly/3C242Bo)

## IPFS AWS Infra:
Run IPFS as a service on AWS with Terraform, for private NFT storages.

[https://github.com/Filedgr/filedgr-ipfs-master](https://github.com/Filedgr/filedgr-ipfs-master)

[https://github.com/Filedgr/filedgr-ipfs-infra](https://github.com/Filedgr/filedgr-ipfs-infra)

## IPFS Python Library

The IPFS pythin library is the library we use in combination with the XRPL CLI to upload the NFT content to our private IPFS infrastructures. Since the existing libraries are not in line with the project anymore, we started the work on our own open source lib.

[https://github.com/Filedgr/filedgr-python-lib-ipfs](https://github.com/Filedgr/filedgr-python-lib-ipfs)





