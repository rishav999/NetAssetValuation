# NetAssetValuation
NAV data extracted from a text file.

Programming Challenge Description:
NAV is the Net Assets Valuation which is the value of the total assets held in a portfolio. Often the portfolio managers try to track a certain benchmark portfolio in terms of the percentage weight of the assets. For instance, consider a portfolio PORT with 3 assets and a benchmark portfolio BENCH with 3 assets:

    PORT                    BENCH
|Stock | Qty|   Price |     Stock |    Qty  |   Price|
  AXN     10      10        AXN     50      10
  BGT     20      30        BGT     30      30
  CXZ     10      30        DFG     30      20
The percentage Nav in stock A for PORT can be calculated as follows:

Nav(PORT) = (Qty(AXN) * Price(AXN))+(Qty(BGT) * Price(BGT))+(Qty(CXZ) * Price(CXZ))

%Nav  = (Qty(AXN) * Price(AXN)) * 100 / Nav(PORT)
A Portfolio is said to be overweight in a stock if its %Nav in that stock is larger than the %Nav in the stock in the Benchmark. Alternately, it is underweight in a stock if its %Nav in a stock is less than the benchmark.

Write a program to calculate the difference in the %Nav of the holdings in the PORT and the BENCH.

Sort the portfolios in alphabetical order and display the difference upto 2 decimal points.
