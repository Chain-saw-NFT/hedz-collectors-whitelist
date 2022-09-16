# Hedz - Chain/Saw Collectors Mint Whitelist
The first phase of the Hedz release is a Chain/Saw Collector Mint. During this phase of the project release, collectors of Chain/Saw's previous NFT collections will be able to mint Hedz based on their current Chain/Saw holdings. The breakdown used to calculate this is as follows:

* 1 Hedz for each Pegz owned
* 1 additional Hedz for having a balance in each of the following Chain/Saw collections:
    * Matt Furie's Rarepepes 
    * Van Minion Blanks
    * Van Minion Genesis 1/1s
    * Infinite Pressure
    * Tozzi Ducks

# Chain/Saw Collector Hedz Allocation
According to the breakdown above, Chain/Saw Collectors have been allocated a total of `626` possible mints. The final number of Hedz minted during this phase will vary depending on Collector turnout.
# How To Check Your Hedz Allowance
If you are a collector of one or more of the collections above, you can check to see how many Hedz you'll be able to mint by looking up your wallet address in `collectorsWhitelist.json` and finding the associated `amount`. For example, the entry below indicates account `0x33ec...20e2` can mint 3 Hedz during the Collectors Mint:

```json
{
  "address": "0x33ec09543037b14640f759eaf4e3576bea3420e2",
  "amount": 3
}
```