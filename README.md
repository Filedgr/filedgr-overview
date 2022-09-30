# filedgr-overview
This repository includes links to different Filedgr repositories. Please note that several of the project may not have a commit history in the last months we moved away from Github in favor of Gitlab for the more powerful CI/CD (in our opinion).

## IPFS AWS Infra:
Run IPFS as a service on AWS with Terraform, for private NFT storages.

[https://github.com/Filedgr/filedgr-ipfs-master](https://github.com/Filedgr/filedgr-ipfs-master)

[https://github.com/Filedgr/filedgr-ipfs-infra](https://github.com/Filedgr/filedgr-ipfs-infra)

## Ripple CLI
__This part of project will stay open source, in the scope of our project we opted for a CLI, for the moment, in order to simply call the function via exec from various programming languages. It also simplifies the setup of our containers with the Gitlab Pypi server. We will also provide a customer facing API based on the CLI Tool.__
We use the Ripple CLI to:
- create wallets
- set trustlines
- issue NFTs, custom tokens with 0.000001 quantity, while waiting for the actual NFT in the mainnet, the memo points to a website hosted on our private IPFS
- issue Transactions tokens: tokens the NFT website is going to check, they contain the lifecycle updates, in the memo



