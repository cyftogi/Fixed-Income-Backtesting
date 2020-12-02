# Fixed-Income-Backtesting
A backtesting framework customized for the credit market

1. Most raw data is fetched from Bloomberg terminal with tia package 
  (https://github.com/bpsmith/tia)

2. FI_class.ipynb: class templates for cash bond, CDX

3. Backtest.ipynb: back test framework  
   - Flexibility: 
     - Users can easily set the start & end dates of backtesting, which hedging instruments to use, the position of each hedging instrument  
     - They can also change the bond portfolio by replacing the data files in the "prices" folder                   
   - Extendability: 
     - can quickly incorporate more hedging tools & analysis
     
4. Hedging Instruments:
   - VXX: iPath Series B S&P 500 VIX Short-Term Futures ETN
   - HYG: iShares iBoxx $ High Yield Corporate Bond ETF
   - EMB: iShares J.P. Morgan USD Emerging Markets Bond ETF
   - CDX HY: Markit’s North American High Yield CDX Index
   - CDX IG: Markit’s North American Investment Grade CDX Index
   - CDX Asia IG: iTraxx Asia ex-Japan index (investment grade)
   - TLT: iShares 20+ Year Treasury Bond ETF
  
  
# Future Improvements: 
1. To allow dynamic testing  
2. Return attribution to each asset class involved




