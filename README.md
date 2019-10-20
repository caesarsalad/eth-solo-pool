# eth-solo-pool
Ethereum Solo Pool

## Used in production for one year.
### Only compatible with parity.
### Nicehash supported with 64G diff (nicehash.json)

To change block reward  payouts/unlocker.go#33 

Use crontab syntax for time intervals of charts at api.json.

You can use screen or tmux to open api, minerproxy,unlocker and payout modules separately. (at production I do not recommend to open all of them in one screen.)

example:
screen -mS api ./build/bin/open-ethereum-pool api.json

# You can open issue on github for bugs. If you need help send e-mail to huseyin-cakir-2013@yandex.com.
____________________
Based on [sammy007/open-ethereum-pool](https://github.com/sammy007/open-ethereum-pool) 
