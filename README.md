# ETHSanFranciscoDemo
Automatic testing system for environmental sensor network using aerial drones

## Step by step technical instruction
1. Transfer control over an autonomous drone base to an Ethereum computer
2. Specify which external owned accounts are authorized to launch missions on a drone base
3. Upload the mission GPS reference points to IPFS
4. Send a transaction to create a mission smart contract using the hash from the last step
5. The drone takes off to deliver a mission from IPFS
6. When the drone returns, it publishes environmental analysis data to IPFS
