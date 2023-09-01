# OCEAN Data NFTs

![GitHub Codespaces](https://img.shields.io/badge/GitHub_Codespaces-%23121011.svg?stylee&logo=github&logoColor=white)

Quickly create [OCEAN](https://oceanprotocol.com/) Data NFTs by querying blockchain data from different providers ([Dune](https://dune.com/) & [Flipside](https://flipsidecrypto.xyz/)).

## Setup
1. Fork this repo.
2. Create a GitHub Codespaces workspace, which will automatically setup a Python environment with the following:
    * Python 3.8.
    * `pip install -r requirements.txt`
3. Copy the `.env.example` file, rename to `.env`, and add your keys:
    * `DUNE_API_KEY`
    * `FLIPSIDE_API_KEY`
    * `WEB3_INFURA_PROJECT_ID` (Note: Must have an Infrura account w/ RPC endpoints.)
    * `PRIVATE_KEY` (For a wallet)
4. Run `Create_OCEAN_Data_NFT.ipynb`

## Video Tutorial
[![Create OCEAN Data NFTs YouTube Video](https://img.youtube.com/vi/ob2k8EPn-_Y/0.jpg)](https://www.youtube.com/watch?v=ob2k8EPn-_Y)

