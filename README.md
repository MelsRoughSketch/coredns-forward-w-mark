# What is this
This fork enables the Dial function used by the forward plugin to be executed within a custom Dialer.

## Change
The following has been added to the *forward* plugin syntax:
```txt
forward FROM TO... {
    fwmark INTEGER
}
```
When forwarding a forward query, packets are sent with the specified fwmark attached.

Enables processing of packets related to fwmark (primarily routing, etc.).


## Considerations
Additional capabilities are required to operate the socket. 

Furthermore, it only works on Linux.

## Disclaimer
Under no circumstances shall I have any liability to you for 
any loss or damage of any kind incurred as a result of theuse of this fork. <br>
Your use of the fork and your reliance on any information is solely at your own risk.