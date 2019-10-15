---
title: US Treasury Yield Curve
date: 2019-10-14T03:09:17.029Z
tags:
  - yield curve
  - federal reserve
draft: true
---
These rates are commonly referred to as "Real Constant Maturity Treasury" rates, or R-CMTs. Real yields on Treasury Inflation Protected Securities (TIPS) at "constant maturity" are interpolated by the U.S. Treasury from Treasury's daily real yield curve. These real market yields are calculated from composites of secondary market quotations obtained by the Federal Reserve Bank of New York. The real yield values are read from the real yield curve at fixed maturities, currently 5, 7, 10, 20, and 30 years. This method provides a real yield for a 10 year maturity, for example, even if no outstanding security has exactly 10 years remaining to maturity. Dataset updated daily every weekday. 

<h2>US Treasury Yield Data</h2> <div class="table-responsive"> <table class="table table-striped table-sm" id="treasuryData"> <thead> <tr> <th>Date</th> <th>1 Month</th> <th>2 Month</th> <th>3 Month</th> <th>6 Month</th> <th>1 Year</th> <th>2 Year</th> <th>3 Year</th> <th>5 Year</th> <th>7 Year</th> <th>10 Year</th> <th>20 Year</th> <th>30 Year</th> </tr> </thead> <tbody> <tr> </tr> </tbody> </table> </div>

<script src="https://finchato.github.io/grabTreasuryData.js"></script>

<h2>US Treasury Yield Curve Shape</h2>

Interesting graph to look at going forward. It is said that the inverted yield curve shape is one of the greatest predictors of economic depression. Of all the financial crisis that happened, most were preceded by an inverted yield curve. To plot the following graph, we take (treasury yield at the 10 year duration period - treasury yield at the 2 year duration period )

Interesting read by The Fed - [(Don't Fear) The Yield Curve](https://www.federalreserve.gov/econres/notes/feds-notes/dont-fear-the-yield-curve-20180628.htm)

<iframe src="https://fred.stlouisfed.org/graph/graph-landing.php?g=lFt2&width=670&height=475" scrolling="no" frameborder="0"style="overflow:hidden; width:670px; height:525px;" allowTransparency="true"></iframe>
