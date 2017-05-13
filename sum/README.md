# Sum

Supposing we have cells **X** and **Y** and we want **Y** to hold the value of **X** + **Y** and **Y**'s position is immediately after **X**'s:

`[ - > + < ]`

The pointer is decrementing **X** and incrementing **Y** in a one-to-one way, like a transfer. Like this, the loop will be over when there's nothing more in **X**'s position to be transferred.
