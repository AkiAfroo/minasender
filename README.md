# minasender :  TESTworld READY !
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

- [x] -added 20 testnet addresses

- [x] -added extra .txt with 1544 testworld address, (carefull you can drain your balance if you set high fees.)

- [x] - auto download the address list ( mina_Users_address.txt )


first lets add your account to .bashrc do the following steps.

in your linux terminal:

`cd`

`nano .bashrc`

at the end of this files.. at this

```
export CODA_PUBLIC_KEY=here-your-wallet
export MINA_PUBLIC_KEY=here-your-wallet
```

change , "here-your-wallet" with your public wallet.

`control` + `o` and hit `ENTER` and `Control` + `x` to exit

now update it with

`source .bashrc`

or close this terminal to changes take effects.

now, download the minasender 

## usage:
* `wget https://raw.githubusercontent.com/AkiAfroo/minasender/main/minasender`
* `chmod +x minasender`
* `bash minasender`
