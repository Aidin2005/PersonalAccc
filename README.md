# PersonalAccc

https://img.plantuml.biz/plantuml/png/TLFBRi8m4BpdArQv55gGsgkbLhJgiNzGLTOIByGYjYDx4K9L_xqcZaC8S8htCPxPyMOL63tlJLCym2Tjj2Me6Wo1Gj5zuTsulMNuBG2MW5qWODCuv2x3sb2ymhG253ATmfJtQ0DMh9sLV6n9G60VAqyWfRQQfPnTNBQuZPZta7YCY7cwvQ_8sgfgB2v5qkxDcdmcFEThrwXnVeqDseekfZbh20A-TE3lDF_FHFerrU8Mps920g_md4PIrBgW-TA4L3fehfN7mwtQsAGwodF-E4kLBR7ioKu-vPdkc_U1TjSxPz7GbL-30IcSE3104Zig9NjSDaVavqaTSRMkMiR-pOV-Ewg7_VJKOFT2jMv3aNUWV2dXSRc4qg0zbdbj1LJECceRuAte9fxszN01CSOjdVfMP5Ny8_u1![Uploading image.png…]()


My code mimics a bank account system:
1. Transaction Tracking
• Every deposit and withdrawal must be an object of class Amount, including both the timestamp of the transaction, along with type.
2. Account Management
• The class Account shall hold information such as account number, holder name, balance, history of transactions as a list, etc.
• Deposit money can be done - increases the amount and adds to the transaction
• Withdraw - provided there is enough balance else throws error.
• The account keeps a history of all transactions.
3. How It Runs
• Creates an account for “John Doe” with an initial balance of 0.
• Deposits $500 and updates the balance.
• Withdraws $200 if there are enough funds.
• Prints the transaction history.
