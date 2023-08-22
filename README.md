# OCEAN Data NFTs

![GitHub Codespaces](https://img.shields.io/badge/GitHub_Codespaces-%23121011.svg?stylee&logo=github&logoColor=white)

Quickly create [OCEAN](https://oceanprotocol.com/) Data NFTs by querying blockchain data from different providers ([Dune](https://dune.com/) & [Flipside](https://flipsidecrypto.xyz/)).

## Setup
1. Create a GitHub Codespaces workspace, which will automatically setup a Python environment with the following:
    * Python 3.8.
    * `pip install -r requirements.txt`
2. Create an `.env` file with the following keys:
    * `DUNE_API_KEY`
    * `FLIPSIDE_API_KEY`
    * `WEB3_INFURA_PROJECT_ID` (Note: Must have an Infrura account w/ RPC endpoints.)
    * `PRIVATE_KEY` (For a wallet)
3. Run `Create_OCEAN_Data_NFT.ipynb`
