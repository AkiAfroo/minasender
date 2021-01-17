# minasender : not ready for TESTworld
## the script
![logo](https://i.postimg.cc/26qDJK34/Mina-Protocol-Sender.png)

## minaexplorer
![logo](https://i.postimg.cc/MKHyL0Yz/Mina-Protocol-Sender2.png)

## Logs
The script save the Dispatched payment with ID inside every address.log files inside minasenderlogs folder
![logo](https://i.postimg.cc/TPfJYKbw/Mina-Protocol-Sender-Logs.png)





# minasender
an easy bash script to send  MINA PROTOCOL tokens ( https://github.com/MinaProtocol/mina ) in Bulk from a LIST of ADDRESS.
the script ask for

- [x] -the amount to send

- [x] -the fee to pay

- [x] -password for unlock your wallet to send those transactions.

- [x] -added 61 testnet addresses

dont forget: you must have a full node synced with all the environment variable ready and setting up in ~/.bashrc or ~/.profile

export CODA_PUBLIC_KEY=your-Mina-Address

export MINA_PUBLIC_KEY=your-Mina-Address-same-as-above

## usage:
* `chmod +x minasender`
* `bash minasender`

# minasender and mina_Users_address.txt must be in the same directory
