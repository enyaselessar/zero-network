<h2 align=center>Contract Deployment on Zero Network</h2>

## Contract Deployment


https://github.com/user-attachments/assets/32cbd0bd-45a4-40f0-a627-355afae551eb


- Bridge atleast 0.01 Sepolia ETH to Zero Network via this [bridge](https://bridge.zero.network/)
- Once you complete bridging to Zero Network, you are now ready to deploy contract on Zero Network
- Open terminal, I used [codespace](https://github.com/codespaces), worked fine, you can use [gitpod](https://gitpod.io/workspaces) as well
- If any of them take long time to open then try to open these in incognito tab, it will open very fast
- Enter the below command to deploy
```bash
wget https://raw.githubusercontent.com/dxzenith/zero-network/main/contract.sh && chmod +x contract.sh && ./contract.sh
```
- In the middle of the code, it will show something like this
```bash
? What do you want to do? … 
  Create a JavaScript project
▸ Create a TypeScript project
  Create a TypeScript project (with Viem)
  Create an empty hardhat.config.js
  Quit
```
- Choose `Create a TypeScript project` option then press `Enter` 4 times
- Done ✅
---
- Make sure to follow [ZunXBT](ZunXBT) on X
