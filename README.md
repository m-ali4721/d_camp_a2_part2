PostgreSQL container:

PostgreSQL init process complete; ready for start up.

2024-01-23 04:36:27.533 UTC [1] LOG:  starting PostgreSQL 16.1 (Debian 16.1-1.pgdg120+1) on x86_64-pc-linux-gnu, compiled by gcc (Debian 12.2.0-14) 12.2.0, 64-bit
2024-01-23 04:36:27.533 UTC [1] LOG:  listening on IPv4 address "0.0.0.0", port 5432
2024-01-23 04:36:27.533 UTC [1] LOG:  listening on IPv6 address "::", port 5432
2024-01-23 04:36:27.540 UTC [1] LOG:  listening on Unix socket "/var/run/postgresql/.s.PGSQL.5432"
2024-01-23 04:36:27.548 UTC [64] LOG:  database system was shut down at 2024-01-23 04:36:27 UTC
2024-01-23 04:36:27.556 UTC [1] LOG:  database system is ready to accept connections
2024-01-23 04:41:27.645 UTC [62] LOG:  checkpoint starting: time
2024-01-23 04:41:31.905 UTC [62] LOG:  checkpoint complete: wrote 45 buffers (0.3%); 0 WAL file(s) added, 0 removed, 0 recycled; write=4.222 s, sync=0.015 s, total=4.260 s; sync files=12, longest=0.012 s, average=0.002 s; distance=261 kB, estimate=261 kB; lsn=0/19544A8, redo lsn=0/1954470


Web Container:

docker logs 71b63ca737aa
 * Serving Flask app 'app'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:8000
 * Running on http://172.26.0.2:8000
Press CTRL+C to quit
172.26.0.1 - - [23/Jan/2024 04:36:27] "GET / HTTP/1.1" 200 -

