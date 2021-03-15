# SQL Antipatterns

_Bill Karwin_

- Closure table: an understandable and a very portable solution for hierarchical data.

- Files can be stored in the database as blobs.

- Horrors of the entity-attribute-value pattern.

- Covering index: if an index contains all columns required in a query, it might not have to read the actual tables at all.

- Check the back seat: when creating new queries from your own data, treat your own database as filled with potentially malicious injection attacks.
