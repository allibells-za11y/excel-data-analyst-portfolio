# Power BI Module 2 — Data Modelling
Dataset: Contoso 100K (SQLBI GitHub · 7 tables · 100,000+ rows)

## What this covers
- Model View: building all 8 relationships with correct cardinality
- Cross-filter direction: single vs bidirectional — when each is correct
- Role-playing Date dimension: active and inactive relationships
- USERELATIONSHIP() in DAX to activate inactive relationships
- Snowflake vs star schema decision (Customer → Geography)
- Ten most common modelling mistakes and how to fix them
- Filter context vs row context — the most important DAX concept
- Measures vs calculated columns — the definitive rule
- Core DAX: SUM, COUNTROWS, DISTINCTCOUNT, DIVIDE, CALCULATE, ALL, ALLEXCEPT, RELATED, SELECTEDVALUE, HASONEVALUE, FILTER
- 12 foundational measures in a dedicated _Measures table
- CALCULATE patterns: override filter, remove filter, FILTER(), USERELATIONSHIP()
- Time intelligence: TOTALYTD, FYTD, SAMEPERIODLASTYEAR, DATEADD, rolling average
- Calculation Groups — 5 items eliminating measure duplication
- Advanced DAX: VAR/RETURN, RANKX, SUMX, LASTNONBLANK (semi-additive), TREATAS, CROSSFILTER, ISINSCOPE
- Performance Analyzer: diagnosing slow visuals
- DAX Query View: EVALUATE queries for measure validation
- Five performance optimisation actions ranked by impact

## Portfolio files
- Model View with all 8 relationships (dashed inactive line visible)
- Calculation Group items in Fields pane
- Performance Analyzer timing screenshot
- DAX Query View EVALUATE result
