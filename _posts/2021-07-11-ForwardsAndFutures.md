---
layout: post
title: "Forwards and Futures"
subtitle: "one of the most common derivatives"
background: '/img/posts/ForwardsAndFutures/01.jpg'
---
<h4> Introduction </h4>
In an earlier post we saw a bit of an introduction to forward/futures and a way they can be used to secure future cashflows. In this post we will be diving into the world of forwards and futures in a bit more detail.

Forwards and Futures are very similar but they are not the same. Following is a table of differences between Forwards and Futures.

<table class="content-table">

  <thead>
    <tr style="background-color: #0085A1 ; color: #ffffff;text-align: center;font-weight: bold;">
      <th>Forwards</th>
      <th>Futures</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>OTC traded</td>
      <td>Exchange traded</td>
    </tr>
     <tr>
      <td>Settled at maturity</td>
      <td>Daily settled/td>
    </tr>
  </tbody>

</table>

<h4> What are the implications of these differences?</h4>

Price Discovery: Since Futures are exchange traded, all the information regarding a particular futures contract is publically available. For example, infromation regarding a gold futures contract expiring next month is readily available in the market. On the other hand, forward contracts are bilateral. There will only be involvement of the two parties and the deal terms and other related information will be held private. So, the information regarding a forward contract is not as transparent as that of a futures contract.

Credit Risk: Since forward contracts are OTC traded, there can be significant exposure to the party making profit if the other party(the one making losses) defaults. On the other hand, if you buy/sell an exchange traded product(here, futures), the only counterparty you ever have to interact with is the exchange itself. 

Is there any chance that an exchange will default? Yes, but its very negligigle. First of all, exchanges are "too big to fail". Also, they have come up with great mechanisms such as <i>margins</i>. If there is a contract traded on an exchange, there will be a party selling the contract to the exchange and another party buying the contract from the exchange. In this way, exchange acts as a middleman. So, there are two deals wrt the exchange. If one deal is making a loss, the other deal is making a profit(I am purposefully excluding commissions to keep it simple). The most obvious threat to an exchange will be when the profit making deal collapses(party defaults). So, as to cover the losses during this mishappening, there will be an account maintained by the exchange for every party it deals with. Ideally, this 'margin' account should have enough money to cover the losses if that particular party defaults. There are several other mechanisms that an exchange has built over the years to prevent itself from defaulting.

Liquidity: Exchange traded products offer more liquidity compared to OTC traded products. Simply put, liquidity is the ease of buying and selling a contract/product without taking a hit on price or time. For example, cash is highly liquid while an exotic interest rate derivative will be less liquid. In other words, If you want to sell/buy a contract, it will be harder to find a buyer/seller for a forward contract than for a futures contract.

<h4> How do you calculate the value of a forward/future contract?</h4>
Assuming that you are already familiar with pricing derivatives using risk binomial model, following is the strike for a forward contract.


<h4> Convexity adjustment between a forward and a future</h4>
