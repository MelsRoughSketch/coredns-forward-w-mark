# What is this
This fork enables the Dial function used by the forward plugin to be executed within a custom Dialer.

Note: This is a modified version of the original project. Please do not contact the original maintainers regarding any issues or bugs found in this fork, as the changes made here are independent of the upstream repository.<br>
All changes following the original commit `3d31397fe65d44f407fa4a1529b1695f10a47c4d` are Copyright 2026 [MelsRoughsketch](https://github.com/MelsRoughSketch).

These changes are also licensed under the Apache Lisence, Version 2.0.


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
