BMTP Core integration/staging repository
=====================================


BMTP is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- Anonymized transactions using coin mixing technology, we call it _Obfuscation_.
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftTX_.
- Decentralized blockchain voting providing for consensus based advancement of the current Masternode
  technology used to secure the network and provide the above features, each Masternode is secured
  with collateral of 1000 BMTP


More information at [bmtpcoin.info](http://www.bmtpcoin.info)

Precompiled binary wallets for various OS can be downloaded here [BMTP Releases](https://github.com/bmtp-project/bmtp/releases)
If you want to compile the wallet yourself, all the necessary documentation is in the [doc](https://github.com/bmtp-project/bmtp/tree/master/doc) folder

We recommend using a special script to install the Masternode. [Install MN script](https://github.com/bmtp-project/bmtp-install)

**Note**: *You can use several Masternodes on one Linux VPS. Each of them should use different P2P and RCP ports, as well as various data dirs. To install the second and subsequent Masternode on the same server, you need manual install and configure it.*

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Algorithm</td><td>Quark</td></tr>
<tr><td>Type</td><td>PoS/MN</td></tr>
<tr><td>P2P port</td><td>42107</td></tr>
<tr><td>RCP port</td><td>42108</td></tr>
<tr><td>Rewards Distribution</td><td>30/70 (PoS/MN)</td></tr>
<tr><td>Masternode Collateral</td><td>1000 BMTP</td></tr>
<tr><td>Premine</td><td>250,000 BMTP</td></tr>
</table>

### Reward depending on the Block Height

<table>
<tr><th>Block Height</th><th colspan=3>Reward Amount</th></tr>
<tr><td>2-1000</td><td>1</td></tr>
<tr><td>1001-3000</td><td>3</td></tr>
<tr><td>3001-5000</td><td>4</td></tr>
<tr><td>5001-10000</td><td>5</td></tr>
<tr><td>10001-50000</td><td>10</td></tr>
<tr><td>50001-100000</td><td>15</td></tr>
<tr><td>100001-500000</td><td>12</td></tr>
<tr><td>500000-1000000</td><td>6</td></tr>
<tr><td>1000000-...</td><td>3</td></tr>
</table>
