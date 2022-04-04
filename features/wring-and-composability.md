---
description: wRING is an utility token.
---

# 💹 wRING & Composability

![](../.gitbook/assets/wring\_small.png)

**Contract**\
****0x59AE8c783eBCe3CC68ccE32C427128101fa4C405

{% hint style="danger" %}
Only use the official dapp [https://app.ringfi.io/#/wrap](https://app.ringfi.io/#/wrap) to wrap and unwrap.
{% endhint %}

wRING or Wrapped $RING is a token that represents the **value** of $RING based on the latest index when you wrap and unwrap respectively.&#x20;

Basically, the amount of wRING doesn’t increase over time, but its value does. Your $RING balance will increase every 15 minutes thanks to the automatic rebases. However, unlike your $RING balance, your wRING balance will not increase over time, but its value will. When wRING is unwrapped, you receive an amount of $RING based on the latest value of the ever-increasing index, so the total yield is the same. That means your wRING is compounding at the same exact rate as $RING thanks to some clever mathematics

{% hint style="info" %}
The team wrote a great Medium to provide a deeper explanation of how you can benefit from wRING and what purposes it serves. [Link](https://medium.com/@ringfi/wring-wrapped-composable-token-by-ringfi-1d1329b80226)
{% endhint %}

{% hint style="success" %}
Also, check out the wRING audit [here. ](https://github.com/coinscope-co/audits/blob/main/wring/audit.pdf)\

{% endhint %}

Since RingFi invented the concept and code to wrap an auto-staking, auto-rebasing token, **no other auto-staking protocol offers this unique feature yet**. This ground breaking innovation has already gained a large amount of attention from the DeFi world. On top of that, the team prioritizes safety and strong, robust code that is audited by third parties like Solidity. In addition to growing your capital, RingFi wants to protect it too.

### How the wrapping works

The entire wrapping and unwrapping process revolves around the index value, an on-chain system that allows the wrapping contract to track and represent how $RING rebases accrue over time.

The index is an imaginary single $RING token inside the contract created at the contract deployment that grows synchronously with the rebases. This allows the contract to know how many $RING tokens you should get when you wrap and unwrap your wRING tokens.&#x20;

The logic behind it is simple: in order to figure out how many wrapped RING (wRING) tokens you will get, simply divide your amount of $RING tokens by the current index value.

To calculate the amount of $RING that you will get from unwrapping your wRING tokens, simply multiply your amount of wRING by the current index value.

### Taxation

wRING tokens follow the same taxation rules as $RING tokens: \
**14% buy tax** \
**16% sell tax**

{% hint style="info" %}
Wrapping, unwrapping, and wallet to wallet transfers are NOT subjected to taxation.&#x20;
{% endhint %}
