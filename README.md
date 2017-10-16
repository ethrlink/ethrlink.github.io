# README - FAQ

## What is ethr.link?
[ethr.link](http://ethr.link) is a link shortener using an ethereum smart contract as its backend. All links are saved on the blockchain and the rest is statically served from github. That's it.

When you buy a short link on ethrlink, you can choose your custom url key and validity period.

See example link (to ethereum.org): [http://ethr.link/ether](http://ethr.link/ether)


## So you're charging money for short links?
Exactly. 

## Why would anyone do this?
First of all it's an experiment for us. We had the idea for a paid link shortener like this some years ago, but didn't actually build it until now. We think ethereum's smart contracts are an amazing opportunity for low priced services like this.

But it also has some advantages for you as the user. You can now get cool urls like [ethr.link/hi](http://ethr.link) and only pay as long you need it. Because of the price tag and the ability to block keys, we expect our site to be used less for malicious links.

## What does an url cost?
Pricing is based on key length (the shorter, the more expensive) and on the validity period.

```
1 character -> 16 milli ether per 30 days
2 character -> 8 milli ether per 30 days
3 character -> 4 milli ether per 30 days
4 character -> 2 milli ether per 30 days
5 character -> 1 milli ether per 30 days
```

## How do I buy a short link?
First you need an ethereum enabled web browser like [Mist](https://github.com/ethereum/mist/releases), [Parity](https://ethcore.io/parity.html), or the [Metamask Chrome Extension](https://metamask.io/).

Visit [ethr.link](http://ethr.link) and the rest should be easy peasy lemon squeezy.

## So do you need an ethereum enabled web browser to visit ethr.link urls?
No. Only if you want to create links. When clicking on ethr.links, everything is readonly and directly fetched via web3.js in the client browser.

## Can I flag malicious links?
Yes. Just file an github issue here. I'll check it and take it down asap.

## Do you have an whitepaper?
No.

## When is the ICO?
Never.

