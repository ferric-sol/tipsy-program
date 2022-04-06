### Tipsy main program

#### Obejctive

Alice wants to tip Bob but does not have his pubkey or wallet address

#### Workflow

1. Alice tips Bob by signing message to assign ownership of token account to TipsyPDA
2. Bob signs in, signs a message to receive tip from TipsyPDA 
3. Tipsy program assigns ownership of token account from Alice to Bob
4. Tip is confirmed

#### Open questions

- How do we assign funds to Bob's wallet/token account only once Bob has signed in and verified their wallet
(one way escrow)