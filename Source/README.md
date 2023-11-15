# Gitopia

# Auto-install Node and Sync via StateSync

```python
wget -O gitopm https://raw.githubusercontent.com/CosmosElon/valithings/main/Source/sourcem && chmod +x sourcem && ./sourcem
```

### Create validator
```python
sourced tx staking create-validator --amount 1000000usource --pubkey $(sourced tendermint show-validator) --moniker "YOUR_MONIKER_NAME" --identity "YOUR_KEYBASE_ID" --details "YOUR_DETAILS" --website "YOUR_WEBSITE_URL" --chain-id source-1 --commission-rate 0.05 --commission-max-rate 0.20 --commission-max-change-rate 0.01 --min-self-delegation 1 --from wallet --gas-adjustment 1.4 --gas auto --gas-prices 0.025usource -y
```
