# EquityAnalyzer
To find investment opportunity and trading signal through fundamental analysis and technical analysis in Bursa Malaysia (KLSE)

# Issue Tracker


1. Fundamental Analysis \n
  a) To collect financial statement for both Annual and Quarter frequency
  b) To generate the overview of company performance using statistical score: 
  
  <ol>        
    i) Altman Z Score, 
    ii) Ohlson O Score (Extended from Z-Score, Likelihood to default in 2 years)
    iii) Beneish M Score (8) - Profit Manipulation, 
    iv) Piotroski F Score (Determine strength of a firm's financial position, avoid value traps)
    v) EBIT / EV (Alternative to PE ratio, take into account of debt)
    vi) Net Cash (Net cash position of a company)
    vii) Market Capitalization (Market value of company outstanding shares)
    viii) 52W Range vs Current Price (Position of share price over last 52 weeks)
  </ol>  
  c) To collect the commodity price and foreign exchange
    i) Rubberwood
    ii) Resin
    iii) Gold
    iv) Lumber
    v) USD/MYR
    vi) Baltic dry
    vii) Crude oil
    viii) Palm oil
    ix) Lumber
    x) Sugar
    xi) Poultry
    xii) Corn
    xiii) Steel
    xiv) Fearix
    
  d) To update the existing data file rather than replacing it

2. Technical Analysis
  a) To collect historical data from yahoo API
  b) Create and define technical indicator
  c) Modelling
    i) Classification - Trading signal (Buy or sell?)
    ii) Regression - Entry Price / Stop loss (Buy/Sell at what price?)

3. Natural Language Processing (NLP) - TBC
  a) Footnote preparation / Remarks
    - To collect and summarize information from quarter report / analyst report 
  b) News / Forum
   - Sentiment Analysis 
   
4. User Interface
  a) Table (Statement, historical share price)
  b) Graph (Historical Share price and the technical indicator)
  c) Trading signal (Search and filter function)
