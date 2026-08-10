European Luxury Operating-Quality Screen

Question

Which company in a five-name European luxury peer set combines the strongest FY2023-FY2025 growth, profitability, balance-sheet resilience, and operating momentum?

Answer in one paragraph

Hermès ranks first in the within-sample operating-quality score and Ferrari ranks second. The result reflects the selected peer set, min-max normalization, and disclosed weights; it is not a stock recommendation because the score does not incorporate current market prices. An illustrative Ferrari DCF produces a base value near EUR 200 per share under the stated assumptions, but the sensitivity table shows that WACC and terminal growth drive a wide valuation range.

Files

European_Luxury_Quality_Screen.xlsx — reported financials, peer scorecard, Ferrari DCF, dashboard, and sources.

European_Luxury_Analysis.ipynb — reproducible calculations and charts.

European_Luxury_Quality_Screen_Deck.pptx / .pdf — executive presentation.

European_Luxury_Quality_Screen_Report.docx / .pdf — written analysis and limitations.

data/luxury_reported_financials.csv — notebook input.

charts/ — exported visualizations.

Method

The score uses five components: revenue CAGR (25%), FY2025 EBIT margin (25%), FY2025 net margin (20%), net cash to revenue (15%), and FY2023-FY2025 EBIT-margin change (15%). Each factor is min-max normalized within the five-company sample. Ferrari’s DCF starts from FY2025 industrial free cash flow and uses explicit annual growth, WACC, terminal-growth, net-debt, and share-count assumptions.

Main limitations

The businesses have different product mixes and accounting profiles.

Min-max scores can be affected heavily by an outlier and by the chosen peer set.

The score measures operating quality, not expected shareholder return.

The Ferrari DCF is illustrative and omits a full three-statement forecast.

A professional valuation would reconcile leases, pensions, minorities, tax, and share-count details more deeply.

Reproduce the analysis

Open a terminal in this folder and run:

jupyter notebook European_Luxury_Analysis.ipynb

Run all cells from top to bottom. The notebook reads the relative path data/luxury_reported_financials.csv and overwrites the charts in charts/.
