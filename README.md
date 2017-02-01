# awesome-postgresql

A curated list of awesome PostgreSQL tools, scripts, slides, and short examples. inspired by the other [awesome lists](https://github.com/bayandin/awesome-awesomeness).

- [awesome-postgresql](https://github.com/devton/awesome-postgresql#awesome-postgresql)
  - [Extensions / Tools](#extensions-and-tools)
  - [Utilities](#utilities)
    - [Useful Scripts] (#useful-scripts)
    - [Useful Examples] (#useful-examples)
    - [Useful Slides](#useful-slides)

### Extensions and Tools
- [Citus](https://github.com/citusdata/citus) - Citus horizontally scales PostgreSQL across commodity servers using sharding and replication. Its query engine parallelizes incoming SQL queries across these servers to enable real-time responses on large datasets.
- [PL/V8](http://pgxn.org/dist/plv8/doc/plv8.html) - Content for starting and do quick consults about PL/V8.
- [PGBouncer](https://pgbouncer.github.io/) - Lightweight connection pooler for PostgreSQL.
- [pgpool-II](http://pgpool.net) - Connection pooler, load balancer, replicator, also implementing parallel query.
- [PGStrom (GPU Process)
](https://wiki.postgresql.org/wiki/PGStrom) - Designed to off-load several CPU intensive workloads to GPU devices.
- [PostgREST](http://postgrest.com/) - Standalone web server that tuns your database directly into a RESTful API.
- [pgloader](http://pgloader.io/) - Load data into PostgreSQL. Any Data.
- [pgbundle](https://github.com/adjust/pgbundle) - Manage your PostgreSQL extensions with Pgbundle.
- [pgcli](http://pgcli.com/) - Postgres CLI with autocompletion and syntax highlighting.
- [Barman](http://www.pgbarman.org) - Backup and recovery manager.
- [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV.
- [pome](https://github.com/rach/pome) - A Postgres Metrics Dashboard which can be deployed as a binary.
- [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) - It's a high speed data loading utility for PostgreSQL. 

#### SQL plan visualizers
- [Depesz](http://explain.depesz.com/)
- [Tatiyants](http://tatiyants.com/pev/)

### Utilities

##### Useful scripts

- [Views dependency handle](http://pretius.com/postgresql-stop-worrying-about-table-and-view-dependencies/) - Script to handle with tabe and view dependencies easy.

##### Useful Examples

- [Listen / Notify in Node.js](http://bjorngylling.com/2011-04-13/postgres-listen-notify-with-node-js.html) - Tiny how to use about listen / notify
- [JSON Queries](http://webrobots.io/postgresql-json-queries/) - Real examples of using lateral joins and recursive queries on JSON structures
- [Using postgresql](http://www.postgresguide.com) - Real examples about using postgresql with awesome examples

##### Useful slides

- [Full text search (PT_BR)](http://pt.slideshare.net/spjuliano/fts-26392077) -  Deep intro on full text search on postgresql
- [PostgREST + Mihtril.js](http://slideshare.net/tonnysk823/using-mithriljs-postgrest-to-build-and-consume-apis) - Real example of postREST using

### Blogs
- [2ndQuadrant](http://blog.2ndquadrant.com/)
- [PostgreSQL-Consulting](http://blog.postgresql-consulting.com/)
- [Depesz](http://www.depesz.com/)

### Screencasts
- [PG Casts](https://www.pgcasts.com/)
