---
category: browser
title: Add Transaction History to LBRY Browser
award: 2000
status: available
date: '2016-07-01'
---

Add a screen showing transaction history the LBRY Browser [`lbry-web-ui`](https://github.com/lbry/lbry-web-ui).

The screen must:

- Display past outgoing and incoming transactions
- Link to the LBRY [block explorer](https://explorer.lbry.io) for transactions

The LBRY daemon already supports an API call, `get_transaction_history` to retrieve transaction history. While running LBRY, type the following in your browser console:

`lbry.call('get_transaction_history', {}, function(response) { console.log(response); });`