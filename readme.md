# Running a Replica node

This repo is setup to easily run curtis testnet replica nodes. Simply run `docker-compose up` to bring a replica node up locally.

The docker image for curtis testnet is hosted in a public docker repo: `public.ecr.aws/i6b2w2n6/nitro-node:curtis3`

The nodeConfig file is prepopulated with curtis testnet parameters. The current setup uses a public rpc url for the Arbitrum Sepolia rpc and stores node data in docker volume.

Replace the arbitrum sepolia rpc url with your own to avoid being rate limited.
