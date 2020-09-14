# Fixed-Income-Backtesting
A backtesting framework customized for the credit market (Cash Bond, CDX)

1. Most raw data is fetched from Bloomberg terminal with tia package 
  (https://github.com/bpsmith/tia)

2. FI_class.ipynb: class templates for cash bond, CDX

3. Backtest.ipynb: back test framework  
   - Flexibility: 
     - Users can easily set the start & end dates of backtesting, which hedging instruments to use, the position of each hedging instrument  
     - They can also change the bond portfolio by replacing the data files in the "prices" folder                   
   - Extendability: 
     - can quickly incorporate more hedging tools & analysis
  
  
# Future Improvements: 
1. To allow dynamic testing  
2. Return attribution to each asset class involved




