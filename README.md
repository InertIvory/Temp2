# Terra Atlas v0.3

Adds a searchable Hydrology tab for named Natural Earth river features and preserves the existing globe and terrain explorer. The terrain API request now sends at most 100 elevation points at once and retries temporary 429/5xx errors.

Run with `pip install -r requirements.txt` then `streamlit run app.py`.

Current river data is generalized Natural Earth 1:110m cartographic linework; it does not provide dependable source/mouth locations, flow direction, discharge, precise lengths or complete country-crossing information. HydroRIVERS and HydroBASINS are planned for a later data integration.
