# CoinMarketCap for Cursor

Read-only cryptocurrency market data and research through the hosted CoinMarketCap MCP server.

## Free access

Use your own free CoinMarketCap Basic account. No paid subscription is required. Optional paid plans provide higher usage limits. Requests use your account's API credits, shared with REST API usage. No separate plugin fee is charged.

## Connect

Install this plugin in Cursor, then authorize the CoinMarketCap MCP connection when prompted. The plugin points to `https://mcp.coinmarketcap.com/mcp` and includes no credentials or server implementation.

For clients that support custom headers instead of browser authorization, follow the official guide to configure `X-CMC-MCP-API-KEY` with your own key. Never commit keys to this repository.

## Try it

- Compare Bitcoin and Ethereum prices and include the data timestamp.
- Give me a crypto market overview with Bitcoin dominance.
- Show Solana's technical indicators and explain them.

Check the returned assets and timestamps. Hosted research requests can take 30–300 seconds; repeating a timed-out request may consume additional credits. This integration does not place trades or transfer funds.

## Package contents and validation

This repository contains the plugin manifest, hosted MCP connection configuration, logo, and documentation. Manifest syntax and local asset references have been checked. End-to-end installation of this wrapper in Cursor has not yet been tested.

## Links

- [Integration guide](https://coinmarketcap.com/api/documentation/ai-agent-hub/mcp/)
- [Privacy](https://coinmarketcap.com/privacy/)
- [Service terms](https://coinmarketcap.com/terms/)
- Support: tech_accounts@coinmarketcap.com

The MIT license covers the files in this repository. The hosted CoinMarketCap service and data remain subject to the service's own terms.
