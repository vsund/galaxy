# Getting started

There are currently two supported operating system installations for Galaxy
Core Software.

1. Installation
   #### Linux (Pi and x86 varieties)
   ```
   bash <(curl -s https://raw.githubusercontent.com/galaxypi/galaxy/master/install.sh)
   ```
   #### macOS
   ```
   bash <(curl -s https://raw.githubusercontent.com/galaxypi/galaxy/master/install-mac.sh)
   ```

2. Navigate to the Galaxy directory

   ```
   cd ~/galaxy
   ```

3. Run the Galaxy blockchain
   The installer should prompt you to type `./galaxyd start` when it is
   finished. This will start syncing the blockchain.

4. Create a Galaxy wallet
   Run the following in a second terminal window
   ```
   ./galaxycli keys add <choose-a-passphrase>
   ```

<br/>
<br/>

```
Welcome to the Galaxy network .................................
```

<br/>

### Receive Galaxy Coin

- Join the [Galaxy Discord](https://discord.gg/36K9nan) chat app.
- Ping one of the [repository maintainers](https://github.com/galaxypi/galaxy#repository-maintainers) and request to receive some Galaxy coin.

### Join the community
- [Follow on Twitter](https://twitter.com/GalaxyPiLab)
- [Contribute](/docs/CONTRIBUTING.md)
- [Create a feature request](https://github.com/galaxypi/galaxy#feature-requests)


### Other instructions

#### Manual installation

Visit the [Manual installation](/docs/manual-install.md) page for manual instructions.

#### Build instructions

Learn more on how Galaxy build works. Visit the [Build instructions](/docs/build-instructions.md)
