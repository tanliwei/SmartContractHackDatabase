# SmartContractHackDatabase
Collected hacks of smart contracts from blogs, twitters, news and etc.

20230217,Daniel Von Fange
No check or adjustment for borrowed funds https://twitter.com/danielvf/status/1626340324103663617?s=20 https://twitter.com/danielvf/status/1626362179904581633?s=20 https://twitter.com/BlockSecTeam/status/1626429280786989056?s=20  
[emergencyWithdraw, lending, logical issue]

20230211,blocksec  
We detected 15 attack transactions (so far) on both Eth and BSC for this same vulnerability. https://twitter.com/BlockSecTeam/status/1624077078852210691  
[Wrong calculation, deflationary token]

20230210,peckshield  
The estimated loss of 02102023's @dForcenet hack is ～$3.65M (w/ 1,236.65 ETH + 719,437 USX on @arbitrum and 1,037,492 USDC on @optimismFND). https://twitter.com/peckshield/status/1623913474513575938  
[price manuplation, lending, liquidation]  

20230210,blocksec  
@dForcenet attacked in both @arbitrum and @optimismFND. The root cause is the well-known read-only reentrancy in the curve pool  https://twitter.com/BlockSecTeam/status/1623901011680333824  
[price manuplation, lending, liquidation]  

20230203,medium,Sperax Team    
USDs Feb 3 Exploit Report from Engineering Team. https://medium.com/sperax/usds-feb-3-exploit-report-from-engineering-team-9f0fd3cef00c  
[rebase]  


20220110,Dedaub and Multichain(Previously Anyswap)  
The hackers deploy the attack contract and set the affected token contract address as its underlying token parameter. Then they can steal the user funds by making calls of anySwapOutUnderlyingWithPermit to AnyswapRouter contract. https://medium.com/multichainorg/multichain-contract-vulnerability-post-mortem-d37bfab237c8 and https://twitter.com/peckshield/status/1625707829188521984(20230215)  
[permit, approval, cross-contract-vulnerability, logical issue]  