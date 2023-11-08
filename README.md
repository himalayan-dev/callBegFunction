# callBegFunction

## How to guide

1. `cp .env.example .env`
2. Update the values for `INFURA_API_KEY` and `PRIVATE_KEY`
3. Call the script with `node index.js 1`. Note that you can tell the script to call the beg function multiple times. For example, if you want to call the beg function 5 times, you would instead do `node index.js 5`
4. Sit back, relax and enjoy the $BEGging

If everything is good, you should see the following output:

```bash
(17:33:01)-(kipkap1001)-(1047)-> node index.js 2
--------------------
Calling the "beg" function #1
Transaction hash: 0x9cf79dca19bb2b045357639345f6680dfac390cd20fb1b1bbe9add26acbbbf9a
--------------------
Calling the "beg" function #2
Transaction hash: 0x13f374d58fc8c60efb4afda98f665bc0b2a29539721f2a173049297bac07c052
```
