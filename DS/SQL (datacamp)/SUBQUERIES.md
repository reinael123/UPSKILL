# [[UPSKILL/DS/SQL (datacamp)/SUBQUERIES|SUBQUERIES]]

![[Pasted image 20250401185404.png]]
# in the [[WHERE statement]]:
![[Pasted image 20250401204657.png]]
![[Pasted image 20250401204712.png]]
![[Pasted image 20250401204716.png]]
# SUBQUERIES IN FROM
so gagawa ka ng isang query tapos ilalagay mo sa from ng main query
![[Pasted image 20250401205032.png]]
# SUBQUERIES IN SELECT
![[Pasted image 20250403052659.png]]
![[Pasted image 20250403052958.png]]
![[Pasted image 20250403053909.png]]
# 3 subqueries in 1 query THATS CRAZY!! 
![[Pasted image 20250403055329.png]]![[Pasted image 20250405065443.png]]
![[Pasted image 20250405065738.png]]
# Nested subqueries

![[Pasted image 20250405070922.png]]

FROM, WHERE AND SELECT

|**Clause**|**Purpose**|**Result Type**|**Use Cases**|
|---|---|---|---|
|**WHERE**|Filters rows based on values from another query (used for comparison).|A single value or set of values.|Filtering data (e.g., checking if a value exists).|
|**FROM**|Treats the subquery as a derived table for further processing (joins, aggregations, etc.).|Table-like result (a temporary table).|Aggregation, filtering, or joining.|
|**SELECT**|Returns calculated values or derived columns for each row.|A scalar value (e.g., number, string).|Adding calculated fields (e.g., rank, totals).|