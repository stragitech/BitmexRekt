#Bitmex Rekt

##	Overview and Origin
Bitmex.com was incorporated in 2014 and is owned by HDR Global Limited in the Seychelles Islands by Arthur Hayes, Ben Delo, and Samuel Reed. Today it is the largest bitcoin derivatives exchange boasting over $1 trillion in 365 day notional trade volume. Its staple Perpetual Bitcoin Futures Contract is the most traded bitcoin instrument. The idea for the company stared out when the co-founder Arthur Hayes was making money on arbitraging with physical cash buying dollar priced bitcoin and selling it in mainland China to profit on the premium. The company was initially funded by money from their friends and family. Over time the three cofounders came together and used their combined experience in investment banking, and high frequency trading systems for hedge funds to build a product that as they believed would benefit from the global shift in the way we use money with bitcoin, and wanted to profit from that change by taking advantage of its volatility. 

##	Business Activities
The fundamental issue that Bitmex does a good job at filling is providing anybody access to financial instruments and leverage. This is in part thanks to their sole use of a Bitcoin and no KYC. Theoretically, Bitmex has a policy of blocking accounts that use IPs in the countries that they cannot operate like the United States, but that could be simply bypassed by a VPN. Bitcoin is a permissionless and censorship resistant payment network, no government can stop the transactions. This allows Bitmex to operate in a bubble where they don’t really have to follow certain regulations like KYC but still have access to virtually everyone in the world. Ten years ago this would be impossible to achieve at this scale and gives the exchanges a big advantage over traditional forex brokers and even many crypto exchanges that handle other currencies.  

All exchange operations are handled through the same API on mobile, desktop, and even institutional clients have equal access to the platform through OpenAPI. 

100% Cold Storage. All funds are kept in offline wallets to reduce risk of hot wallet breaches. The industry standard used to be around 97-99% the time Bitmex started, these days though Bitmex’s direct competitor Bybit is using 100% and Bitfinex is at 99.5%. Storing funds in hot wallets is a method to allow fast withdrawals and less friction for users at the cost of security of the funds. Bitmex only allows withdrawals once a day, which would be a lot more problematic for a regular exchange to maintain as their users would have reduced access to short term arbitrage and be wearier about keeping a larger portion of their portfolio on the exchange. This however is not a problem for Bitmex since their users already don’t have as much money on the exchange to begin with because of the leverage they have access to, and the access to that leverage is what also allows them to arbitrage so the exchange rate wont drift as much from the index. 

Multi-signature exchange cold wallets are also the key to a higher degree of security since they require at a minimum 2 out of 2 keys to sign the transaction before it can be broadcasted to the network thereby making it more difficult to gain access to funds. However, 2 of 2 methods is usually forgone for 2 of 3, or higher. Redundancy is the reasoning behind this as it reduces the probability of losing access to client funds forever and discourages bad actors from threatening or even kidnapping key holders. Which is extreme as it seems has already happened to a bitcoin exchange owner in Ukraine in December of 2018 and is yet another attack vector that exchanges must consider. Multisig wallets become a more sought-after feature after the CEO of QuadrigaCX died or disappeared with sole access to millions of dollars in client funds. 

‘Order Shedding’ is a key strategy that the Bitmex trading engine utilizes. Instead of piling up more orders at the end of a queue during times of high order through put and likely volatility. It maintains a an artificial cap on the maximum order queue and ‘sheds’ new orders until it is below their threshold. The upside to this is that orders placed at vastly different times will probably be at different prices so you may actually not want to make the trade you sent 5 or 10 seconds ago. Many customers however are not very happy with their orders getting cancelled when they want to trade and they criticize the exchange for the “its not a bug it’s a feature” way of thinking.

Kdb+ is a proprietary database commonly used in high-frequency trading to store, analyze and retrieve large data sets at high speed. In May 2018 Bitmex optimized its trading engine with kdb+ and improved its performance by 4.6x in the first 30 days and 10x by the end of August. 
Post kdb+ optimization
http://prntscr.com/oo1oen

##	Landscape
The first bitcoin transaction occurred on January 12th, 2009 between Satoshi Nakamoto and Hal Finney. At the time the cypherpunk mailing list was the cryptocurrency community. The global financial crisis was still ongoing with the German Chancellor on the brink of Second Bailout. Until February 6th bitcoin had no exchange value, only theoretical cost to produce a block in terms of electricity depending on the difficulty and hash rate. That all changed with BitcoinMarket which gave users a way to deposit dollars though Paypal, which worked great until the space grew and with-it fraud and chargebacks until Paypal was dropped and exchange later discontinued.

Rapid expansion of the space over time has proven to be a difficult thing for exchanges to contend with. bitcoin exchanges live and die by their ability to scale during frenzies and find a strong niche in the market. Scaling points that should be addressed along with an exchanges growth in deposits are; internal and account security, efficiency of the trading engine, ability to onboard new users, regulatory compliance especially for often exploited loopholes, and customer service for issues. This is all put to the test once there is a period of high volatility, especially when the Cryptocurrency market is experiencing rapid growth or near market tops. A great example of this is December 7th of 2017 when bitcoin had opened the trading day at 14090 on Coinbase and as retail traders started waking up in the U.S. exploded to 19697 and overshot Bitmex by 1947 dollars! Even through it is usually derivatives platforms that skew more into the direction of the trend due to liquidations, the sheer number of new users were buying in crashed the site and added to the panic sell off on the reversal. Moments like this point out bottlenecks that give some idea of the limit of these growth spurs and reflect negatively on the industry in the short term, but they also bring out opportunities for other players to step in. Binance has grown to be the biggest spot exchange by volume in 2018 having started in Q4 of 2017  in part, because they were able to keep accepting new users with no KYC as their competitors struggled to meet large volumes of requests and discontinued sign ups or had long verification times when everyone was rushing in to trade to the point of paying thousands of dollars for just a verified account credentials on what was is just a mid-level altcoin exchange.  This along with the boom in altcoins that Binance was quick to list, allowed it to cut out its share in the market for some time.

##	Results
Since Bitmex’s establishment in 2014 has grown to become the industry standard in high leverage bitcoin futures. It has transformed the popular 20x weekly and quarterly OKCoin futures products of 2015-2016 to 100x Perpetual Bitcoin Futures Contract.

Trust in the exchanges ability to handle funds is quite high since the system’s auto audit system has avoided user balance errors and especially breaches. It is one of the few exchanges from that time and in general that has not lost customer funds to hackers.

The massive 30k BTC insurance fund that continues growing a crucial part of Bitmex’s value proposition.  Prior to Bitmex’s takeover of the volume dominance in 2017 its competitors struggled to maintain more than a couple bad weeks’ worth of losses and every few months would have to socialize losses by taking from profits on winning positions of that week. This leads to much higher implied risk for hedging your positions on the exchange because as you lose money on your underlying asset, you might get a 20 -30% haircut on your leveraged positions because too many people lost money that week. Thereby making hedging risky and economically inefficient. A large insurance fund allows traders to have more confidence in longer term positions. Another benefit is theoretically improved incentives for those that are liquidated to pay for those that lost more than their margin without putting them in debt like in the legacy financial markets. Although that benefit does come at a cost of some of their left over margin if they haven’t lost more than they put in. 

Bitmex Insurance Fund
http://prntscr.com/oo0wix

Bitmex is the largest player in its niche of crypto derivatives, but some large exchanges like Bitifnex and Binance are trying to go after their high leverage advantage by offering 100x margin and altcoin margin respectively. Its current direct competitor Deribit, is also offering a product Bitmex does not options. Derbit was the first significant crypto options platform that is right now sitting in a growing niche where it is the sole player with Bitmex reportedly 9 – 15 months behind on their own public bitcoin options. 

##	Recommendations
Options are a confirmed and obvious but necessary route if Bitmex wants to stay in the lead of big regulated players like LedgerX and especially if it does not want to lose the unregulated market to Deribit. 
Custom financial indices of developing markets to give people more financial tools. Although this would be in line to their stated vision of global inclusion, the actual implementation would prove somewhat troublesome because of financial regulations and the actual possible index may not be the best.

Bitmex has already announced that it is planning on rolling out zero coupon bitcoin bonds to allow users to earn interest on their bitcoin by giving short term loans to large crypto companies. This is an entirely new market and instrument that they are opening up and pricing that retail traders have not had access to. This might become one of the first big attempts at bitcoin interest bearing accounts and may change the way people perceive holding bitcoin or holding bitcoin on an exchange. 



https://en.wikipedia.org/wiki/BitMEX
https://www.bitmex.com/app/aboutUs
https://www.youtube.com/watch?v=fQpQgaNyZEw
https://blog.bitmex.com/the-bitmex-insurance-fund/
https://blog.bitmex.com/bitmex-market-making-desk/?source=post_page---------------------------
https://blog.bitmex.com/bitmex-technology-scaling-part-1/
https://medium.com/@BitMEX/bitmex-technology-scaling-part-2-the-road-to-100x-975345422439
https://www.bitmex.com/app/perpetualContractsGuide#Funding-Rate-Calculations
https://cointelegraph.com/news/roubini-bitmex-in-violation-of-securities-laws-crypto-a-metastasized-cancer
https://cointelegraph.com/news/quadrigacx-users-lose-190m-as-speculations-over-cottens-death-swirl
https://www.businessinsider.com/exmo-bitcoin-ceo-pavel-lerner-kidnapped-in-ukraine-2017-12
https://charts.cointrader.pro/charts.html?coin=INSURANCE-FUND%3ABTC
https://info.binance.com/en/research/marketresearch/cryptoasset-cycles.html
https://coincenter.org/entry/what-is-multi-sig-and-what-can-it-do
https://en.bitcoin.it/wiki/Cold_storage
https://swagger.io/specification/
https://support.bitfinex.com/hc/en-us/articles/213892469-Bitfinex-Security-Features
https://en.bitcoinwiki.org/wiki/Bitcoin_history
https://www.worldbank.org/en/publication/gfdr/gfdr-2016/background/financial-access
https://cointelegraph.com/news/bitmex-ceo-arthur-hayes-reveals-plans-to-open-crypto-options-platform
https://finance.yahoo.com/news/bitmex-launch-bitcoin-zero-coupon-114404924.html
https://bitcointalk.org/index.php?topic=2706641.0
https://www.deribit.com/pages/docs/general
