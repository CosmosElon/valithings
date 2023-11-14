# Gitopia

# Auto-install Node

```python
wget -O gitopm https://raw.githubusercontent.com/CosmosElon/valithings/main/gitopia/gitopm && chmod +x gitopm && ./gitopm
```

### Create validator
```python
gitopiad tx staking create-validator \
  --amount 1000000ulore \
  --from <walletName> \
  --commission-max-change-rate "0.1" \
  --commission-max-rate "0.2" \
  --commission-rate "0.1" \
  --min-self-delegation "1" \
  --pubkey  $(gitopiad tendermint show-validator) \
  --moniker "" \
  --chain-id gitopia \
  --identity="" \
  --details="" \
  --website="" -y
```
