---
# This file is licensed under the MIT License (MIT) available on
# http://opensource.org/licenses/MIT.

layout: base-core
lang: en
id: full-node
title: "Running A Full Node - Reddcoin"
end_of_page: |
  <script>updateToc();</script>
  <script>accordion();</script>
  <script>onScrollButton();</script>
  <script>boxShow();</script>
breadcrumbs:
  - reddcoin
  - rdd
  - rdd documentation
  - Bandwidth sharing
---

<!-- Variable assignment

{% capture installFinished %}
You have now completed installing Reddcoin Core.  If you have any questions, please ask in one of Reddcoin's many [communities](/en/community), such as [Reddcoin Talk](https://reddcointalk.org/), [Reddcoin Discord technical support](https://discord.gg/vKyEVnw), or the [#reddcoin official Telegram](https://t.me/ReddcoinOfficial) on Freenode.

To support the Reddcoin network or/and Stake, you also need to allow incoming
connections. Please read the [Network
Configuration](#network-configuration) section for details.
{% endcapture %}

-->

<br/> .
<br/> .
<br/> .


# Running A Full Node
A full node is a program that fully validates transactions and blocks. Almost all full nodes also help the network by accepting transactions and blocks from other full nodes, validating those transactions and blocks, and then relaying them to further full nodes.

Most full nodes also serve lightweight clients by allowing them to transmit their transactions to the network and by notifying them when a transaction affects their wallet. If not enough nodes perform this function, clients won't be able to connect through the peer-to-peer network---they'll have to use centralized services instead.

Many people and organizations volunteer to run full nodes using spare computing and bandwidth resources---but more volunteers are needed to allow Bitcoin to continue to grow. This document describes how you can help and what helping will cost you.
