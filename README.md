# Soulbound
Proof ownership of World of Warcraft character NFT, using OAuth & LINK.
Gets data from Batte.net API using custom external adapter → stores data (images, achievements) on IPFS→mints NFT onchain.

_For the scope of the hackathon we will focus on World of Warcraft._

## User story
* User connects wallet
* User signs in with Battle.net (OAuth integration)
* Selects a character he owns
* Mints NFT (character image & related data stored on IPFS)

# Installation

## Front-end

Install node modules
`npm install`

Start app
`npm run dev`

## External Adapter

* Run external adapter code as docker container on LINK node machine
* Log in to LINK node dashboard and create a bridge to adapter

## Contracts

* Deploy
* Set oracle/job params