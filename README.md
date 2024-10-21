# ChainControl Verification Tool
This binary is used by the ChainControl GitHub Action for verifying smart contract deployments.
## Usage Instructions
1. Set up the following environment variables:
   - `CHAINCONTROL_API_KEY`: Your ChainControl API key
   - `ETHERSCAN_API_KEY`: Your Etherscan API key
   - Add API keys for other chain explorers as needed (e.g., `BSCSCAN_API_KEY`, `POLYGONSCAN_API_KEY`, etc.)
2. Create a `chainControl.json` configuration file in your repository with contract details.
3. Run the binary, specifying the path to your config file:
`./ChainControl_agent --config-file path/to/chainControl.json`

For more detailed information, refer to the full documentation.
