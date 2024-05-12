![image](https://github.com/TronixFoundation/documentation/assets/169593036/f8b7fa90-56c1-42f1-91be-a863f82b36ed)

We started migrating Tron tokens from the old ERC20 to the new TRX20 standard, a native token for the Tron Mainnet which can be used on any exchange which have Tron listed. Tron holders can swap their old ERC20 TRX for the new TRX20 by using a migration contract. To avoid confusion, TRX20 and TRC20 are the same standards.

## How to migrate TRX tokens from the Ethereum tokens to the Tron Mainnet?

> This is a 1:1 swap, which means that anyone who holds the ERC20 token will receive the same amount of TRX20 tokens. There is no reduction in the token supply.

For any remaining TRX ERC20 tokens which were not migrated yet, we decided to conduct the migration by directly using a migration smart contract, instead of using a migration user interface that is not supported anymore. This makes the migration process for the remaining old Tron ERC20 tokens holders fast and simple. We suggest that every holder of old ERC20 tokens perform the migration as soon as possible to avoid possible.

Using a migration smart contract, which is created only for migration purposes, allows you to migrate your TRX tokens without having to connect to any external platforms. Migration smart contract address is open-source which means code is publicly available and can be checked by anyone on the Blockchain.

Using a migration contract requires users to pay the gas fee on Ethereum Blockchain. This means that every user who wants to perform migration needs to have ETH on their wallet. Migration is a similar process to any other transaction on the Ethereum Blockchain and the gas fee is the same as any other transaction. We recommend choosing the average (normal) gas fee to avoid any inconvenience.

The migration can be conducted with the wallet which you usually use to access the TRON tokens. The most commonly used wallets for storing old ERC20 TRX tokens were MyEtherWallet, Ledger, MetaMask, Klever, Exodus, Bitpie, Trust Wallet, Atomic Wallet, Math Wallet, Cobo, TokenPocket, Vision, Bitkeep, Guarda, Moonstake. All these wallets support the migration process.

The migration procedure is the same for any other non-custodial wallets which you use to store ERC20 tokens, like old ERC20 TRX. In some rare cases, your wallet could not support the migration, because some wallets may not support the new Tron Mainnet. In this case, you will receive your ERC20 TRX back from the migration contract. This is how you will know that your wallet is not supporting migration. If the wallet support TRC20 tokens then it supports the migration.

To perform the migration, first, access your wallet to see your Tron balance on the list of Ethereum tokens. Now send your old ERC20 TRX tokens to the migration smart contract address which is `0x49aD4CeD7F8B1aF642B3F6129ead6D4339039050`. The Migration smart contract address begins with the `0x49` and ends with the `9050`, please check that it is correct. 

For the amount choose to send the entire TRX balance, otherwise, the migration process will not start. The contract is waiting for the whole balance to be received before performing the migration to save on high ETH fees which are covered by Tron Foundation. Users just need to pay a regular transaction fee to send the tokens to the migration contract address.

After the transaction is confirmed and broadcasted to Blockchain, the migration process will start and your wallet will be credited with new TRX tokens. It may take 10–30 minutes to process the migration if network usage is high.

Your wallet will automatically recognize the new Tron Mainnet and TRX will be credited to your wallet. The public address of your Tron Mainnet wallet will look different from your Ethereum address where ERC20 TRX was stored. This is because Tron Mainnet’s public address is just a derivation of the Ethereum public address, which uses a different hash algorithm for addresses. The migration contract will still know where to send new migrated tokens. Your new Mainnet TRC20 TRX tokens will be tied to the same private key and seed.

Now, when migration is performed, you have new TRX tokens in your wallet. Tokens can be sold on any exchange which listed Tron. Nowadays, all exchanges support the new Tron Mainnet instead of the old one.

For the, it will be required to install the Tron app in the Ledger manager to be able to view the new TRX tokens after the migration. If you already have a Tron app when performing the migration, the new TRX will just show up in your TRX balance.

**Congratulations, you have successfully perform the migration.**
