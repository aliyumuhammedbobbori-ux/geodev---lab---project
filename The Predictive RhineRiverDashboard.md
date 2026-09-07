Project Title
Can Machine Learning Predict Critical Water Level Drops at the Kaub Choke Point of Rhine River to Safeguard European Cargo Supply Chains?
Why This Solution Matters
The Rhine River is a vital economic artery for European trade, but intensifying summer droughts have repeatedly forced cargo ships to operate at drastically reduced capacities or halt completely. By using machine learning to accurately forecast water levels 7 to 14 days in advance, logistics operators can proactively optimize vessel cargo loads, schedule alternative freight routes, and prevent severe industrial supply chain bottlenecks. This proactive spatial dashboard transforms passive climate observation into an actionable risk-management tool for the entire European inland shipping sector.
Required Data & Sources
•	Historical Water Levels: Daily gauge heights and discharge rates at key choke points via the BfG PEGELONLINE API.
•	Historical Climate Grids: Daily precipitation, temperature, and snowmelt data in the Rhine basin via the DWD Open Data Portal.
•	Upstream Catchment Inflows: Water discharge volumes entering Germany from cross-border tributaries via the Swiss FOEN Data Portal.
•	Future Weather Forecasts: 14-day rainfall and temperature projections for the catchment zone via the Open-Meteo API.
Project Outcome
The final outcome will be an interactive, web-based GIS dashboard built with Python (Streamlit and Folium) that displays a live, color-coded map of critical Rhine shipping checkpoints. Behind the interface, a time-series machine learning model (such as an LSTM or XGBoost Regressor) will ingest live weather forecasts and hydrological data to predict exact water levels up to two weeks into the future. The dashboard will dynamically flag impending low-water risks, allowing users to hover over map gauges to see predictive trend lines and automatically receive warnings when water levels are projected to drop below safe navigation thresholds.
