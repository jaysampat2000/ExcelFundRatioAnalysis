1. Get monthly vals from Yahoo Finance. Convert to Returns. Use adj close
2. Go to Ken French data and download. Convert each col to %	
3. number of rows should line up exactly before regression - same start and end dates	
4. Calculate Avg Mkt-Rf, Avg ARKK-Rf, Stdev of ARKK-Rf, Stdev of MRP. Monthly and Annualized	
5. Regress Y [ARKK-rf] (calculated value) onto X [Mkt-Rf] (no change)	
6. Calculate Annualized Alpha and write out CAPM equation	
7. Calculate:

  1) stdev of residuals, monthly
	2) stdev of residuals, annualized
  3) info ratio
  4) annualized MRP
  5) ARKK portfolio retn using CAPM
  6) annualized stdev of ARKK fund returns
  7) sharpe ratio for ARKK
  8) treynor ratio for ARKK
  9) sharpe for Mkt
  10) Treynor for Mkt
