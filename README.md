# Igris Terminal — V0 prototype

A static, interactive prototype for the Igris Capital market-structure terminal.

## Current experience
- Macro market pulse and illustrative bull/bear balance
- Participant activity and market breadth panels
- Clickable sector list
- 12 illustrative stocks per sector
- Search and sort controls
- Click-through stock details with conceptual support/resistance (order-block-style) zones
- Responsive dark terminal UI

## Important data limitation
All prices, percentages, participant figures, sentiment scores, and order-block zones in this version are **illustrative placeholders**. No live market data, broker connection, order execution, or verified institutional order-flow data is connected. The UI must not be presented as a live trading signal product.

## Deploying later
This is a static single-page app and can be hosted with GitHub Pages or another static host. Configure the custom domain `terminal.igriscapital.in` only after hosting is enabled and DNS is ready. Do not add a CNAME file until the hosting configuration is intentionally set.

## Next development steps
1. Finalize design and data definitions with Joy.
2. Decide the first real data source and licensing terms.
3. Implement validated calculations for participant bias, sector strength, and order-block zones.
4. Add robust loading/error states and testing.
5. Configure hosting and the custom subdomain after approval.
