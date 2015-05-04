Fri May  1 18:38:10 BST 2015
no thinktime
Linux ECSPGSQL 3.0.76-0.11-default #1 SMP Fri Jun 14 08:21:43 UTC 2013 (ccab990) s390x s390x s390x GNU/Linux
Command line: /home/mark/bin/dbt2-run-workload -a pgsql -c 80 -d 600 -w 4 -o z-dbt2-w8 -s 100 -z no thinktime -p -c max_connections=100 -c checkpoint_segments=180 -c checkpoint_timeout=30min -c shared_buffers=2GB -c work_mem=16MB -r -n
Database Scale Factor: 4 warehouses
Test Duration: 600 seconds
Database Connections: 80
