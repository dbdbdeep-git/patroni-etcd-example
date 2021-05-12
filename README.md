ref : https://github.com/zalando/patroni

# patroni-example
- ./0_build.sh
- ./1_run.sh
- ./2_patronictl.sh list
+ Cluster: demo (6961236670416973853) ------+----+-----------+
| Member   | Host       | Role    | State   | TL | Lag in MB |
+----------+------------+---------+---------+----+-----------+
| patroni1 | 172.23.0.8 | Leader  | running |  2 |           |
| patroni2 | 172.23.0.7 | Replica | running |  2 |         0 |
| patroni3 | 172.23.0.6 | Replica | running |  2 |         0 |
+----------+------------+---------+---------+----+-----------+
- ./3_conn_test.sh
