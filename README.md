# Useful_PLSQL_Queries
These are simple Oracle PL/SQL queries which are generally useful for searching and troubleshooting.

"Search All Columns in All Tables.sql" uses the all_tab_columns table to search across all columns in all tables for tables containing a column which matches text. It also gives the ordinal position of the column in the table and its datatype. To use, insert the search term into "WHERE COLUMN_NAME LIKE '%<search_term>%'.

PL/SQL is case-sensitive with matching text.
