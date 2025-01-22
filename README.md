cd myLUKSOnode

sudo lukso stop

sudo rm -rf mainnet-data/consensus

sudo rm -rf mainnet-data/execution

sudo lukso start --validator --transaction-fee-recipient "YOUR WALLET" --checkpoint-sync
