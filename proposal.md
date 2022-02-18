# Utilizing FTD data as a Prediction Metric

On a bi weekly basis, market makers are required to report fail-to-deliver (FTD) data.

Failure-to-deliver (FTD) refers to a situation where one party in a trading contract (whether it's shares, futures, options, or forward contracts) doesn't deliver on their obligation. Such failures occur when a buyer (the party with a long position) doesn't have enough money to take delivery and pay for the transaction at settlement.

A failure can also occur when the seller (the party with a short position) does not own all or any of the underlying assets required at settlement, and so cannot make the delivery.

It is belived that GameStop ($GME) is still heavily shorted even though the short interest value has come down since the whole fiasco began in Jan 2020.

In short, I want to use this publicly available data provided by the SEC to figure out if we can extact any valuable information on the underlying stock -- in particular, $GME.


This project will be worked on solely by myself.


The data can be obtained from [here.](https://www.sec.gov/data/foiadocsfailsdatahtm)

This dataset cotains file date, CUSIP numbers (identifies each individual company), the ticker symbol, issuer name, price, and total number of fail-to-delivers.

I will propose 3 questions/tasks:

<ol>
  <li>1. Is it possible to predict price fluctuations based on patterns in FTD vs delivery date?
  <li>2. Are FTDs a viable signal for synthetic operations (even possible)?
  <li>3. Visualize key FTD values/dates in relation to the market at large.
</ol>
