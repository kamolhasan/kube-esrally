```        
    ____        ____
   / __ \____ _/ / /_  __
  / /_/ / __ `/ / / / / /
 / _, _/ /_/ / / / /_/ /
/_/ |_|\__,_/_/_/\__, /
                /____/
```
[INFO] You did not provide an explicit timeout in the client options. Assuming default of 10 seconds.
[INFO] Downloading track data (252.9 MB total size)                               [100.0%]
[INFO] Decompressing track data from [/root/.rally/benchmarks/data/geonames/documents-2.json.bz2] to [/root/.rally/benchmarks/data/geonames/documents-2.json] (resulting size: [3.30] GB) ... [OK]
[INFO] Preparing file offset table for [/root/.rally/benchmarks/data/geonames/documents-2.json] ... [OK]
[INFO] Racing on track [geonames], challenge [append-no-conflicts] and car ['external'] with version [7.14.0].

[WARNING] merges_total_time is 3607 ms indicating that the cluster is not in a defined clean state. Recorded index time metrics may be misleading.
[WARNING] flush_total_time is 2119 ms indicating that the cluster is not in a defined clean state. Recorded index time metrics may be misleading.
```
Running delete-index                                                           [100% done]
Running create-index                                                           [100% done]
Running check-cluster-health                                                   [100% done]
Running index-append                                                           [100% done]
Running refresh-after-index                                                    [100% done]
Running force-merge                                                            [100% done]
Running refresh-after-force-merge                                              [100% done]
Running wait-until-merges-finish                                               [100% done]
Running index-stats                                                            [100% done]
Running node-stats                                                             [100% done]
Running default                                                                [100% done]
Running term                                                                   [100% done]
Running phrase                                                                 [100% done]
Running country_agg_uncached                                                   [100% done]
Running country_agg_cached                                                     [100% done]
Running scroll                                                                 [100% done]
Running expression                                                             [100% done]
Running painless_static                                                        [100% done]
Running painless_dynamic                                                       [100% done]
Running decay_geo_gauss_function_score                                         [100% done]
Running decay_geo_gauss_script_score                                           [100% done]
Running field_value_function_score                                             [100% done]
Running field_value_script_score                                               [100% done]
Running large_terms                                                            [100% done]
Running large_filtered_terms                                                   [100% done]
Running large_prohibited_terms                                                 [100% done]
Running desc_sort_population                                                   [100% done]
Running asc_sort_population                                                    [100% done]
Running asc_sort_with_after_population                                         [100% done]
Running desc_sort_geonameid                                                    [100% done]
Running desc_sort_with_after_geonameid                                         [100% done]
Running asc_sort_geonameid                                                     [100% done]
Running asc_sort_with_after_geonameid                                          [100% done]
```

```
    _______             __   _____
   / ____(_)___  ____ _/ /  / ___/_________  ________
  / /_  / / __ \/ __ `/ /   \__ \/ ___/ __ \/ ___/ _ \
 / __/ / / / / / /_/ / /   ___/ / /__/ /_/ / /  /  __/
/_/   /_/_/ /_/\__,_/_/   /____/\___/\____/_/   \___/
```


|                                                         Metric |                           Task |       Value |    Unit |
|---------------------------------------------------------------:|-------------------------------:|------------:|--------:|
|                     Cumulative indexing time of primary shards |                                |     11.3102 |     min |
|             Min cumulative indexing time across primary shards |                                |     0.02955 |     min |
|          Median cumulative indexing time across primary shards |                                |     2.13856 |     min |
|             Max cumulative indexing time across primary shards |                                |     2.58377 |     min |
|            Cumulative indexing throttle time of primary shards |                                |           0 |     min |
|    Min cumulative indexing throttle time across primary shards |                                |           0 |     min |
| Median cumulative indexing throttle time across primary shards |                                |           0 |     min |
|    Max cumulative indexing throttle time across primary shards |                                |           0 |     min |
|                        Cumulative merge time of primary shards |                                |     5.54985 |     min |
|                       Cumulative merge count of primary shards |                                |          16 |         |
|                Min cumulative merge time across primary shards |                                |   0.0601167 |     min |
|             Median cumulative merge time across primary shards |                                |     1.03395 |     min |
|                Max cumulative merge time across primary shards |                                |     1.43058 |     min |
|               Cumulative merge throttle time of primary shards |                                |      0.6427 |     min |
|       Min cumulative merge throttle time across primary shards |                                |           0 |     min |
|    Median cumulative merge throttle time across primary shards |                                |    0.128658 |     min |
|       Max cumulative merge throttle time across primary shards |                                |    0.158183 |     min |
|                      Cumulative refresh time of primary shards |                                |     4.15372 |     min |
|                     Cumulative refresh count of primary shards |                                |         245 |         |
|              Min cumulative refresh time across primary shards |                                |  0.00841667 |     min |
|           Median cumulative refresh time across primary shards |                                |    0.931158 |     min |
|              Max cumulative refresh time across primary shards |                                |     1.06313 |     min |
|                        Cumulative flush time of primary shards |                                |      0.2449 |     min |
|                       Cumulative flush count of primary shards |                                |          14 |         |
|                Min cumulative flush time across primary shards |                                |   0.0205167 |     min |
|             Median cumulative flush time across primary shards |                                |   0.0355417 |     min |
|                Max cumulative flush time across primary shards |                                |   0.0772333 |     min |
|                                        Total Young Gen GC time |                                |      77.438 |       s |
|                                       Total Young Gen GC count |                                |        4158 |         |
|                                          Total Old Gen GC time |                                |           0 |       s |
|                                         Total Old Gen GC count |                                |           0 |         |
|                                                     Store size |                                |     2.73347 |      GB |
|                                                  Translog size |                                | 3.58559e-07 |      GB |
|                                         Heap used for segments |                                |    0.756332 |      MB |
|                                       Heap used for doc values |                                |   0.0359802 |      MB |
|                                            Heap used for terms |                                |    0.588165 |      MB |
|                                            Heap used for norms |                                |   0.0797119 |      MB |
|                                           Heap used for points |                                |           0 |      MB |
|                                    Heap used for stored fields |                                |    0.052475 |      MB |
|                                                  Segment count |                                |         106 |         |
|                                                 Min Throughput |                   index-append |     21583.8 |  docs/s |
|                                                Mean Throughput |                   index-append |     22424.3 |  docs/s |
|                                              Median Throughput |                   index-append |     22438.2 |  docs/s |
|                                                 Max Throughput |                   index-append |     23005.4 |  docs/s |
|                                        50th percentile latency |                   index-append |     1663.49 |      ms |
|                                        90th percentile latency |                   index-append |     2244.09 |      ms |
|                                        99th percentile latency |                   index-append |     3204.49 |      ms |
|                                      99.9th percentile latency |                   index-append |     4079.35 |      ms |
|                                       100th percentile latency |                   index-append |     4156.13 |      ms |
|                                   50th percentile service time |                   index-append |     1663.49 |      ms |
|                                   90th percentile service time |                   index-append |     2244.09 |      ms |
|                                   99th percentile service time |                   index-append |     3204.49 |      ms |
|                                 99.9th percentile service time |                   index-append |     4079.35 |      ms |
|                                  100th percentile service time |                   index-append |     4156.13 |      ms |
|                                                     error rate |                   index-append |           0 |       % |
|                                                 Min Throughput |                    index-stats |       89.69 |   ops/s |
|                                                Mean Throughput |                    index-stats |       89.81 |   ops/s |
|                                              Median Throughput |                    index-stats |       89.83 |   ops/s |
|                                                 Max Throughput |                    index-stats |       89.89 |   ops/s |
|                                        50th percentile latency |                    index-stats |     4.38379 |      ms |
|                                        90th percentile latency |                    index-stats |     5.41687 |      ms |
|                                        99th percentile latency |                    index-stats |     11.7487 |      ms |
|                                      99.9th percentile latency |                    index-stats |     19.5678 |      ms |
|                                       100th percentile latency |                    index-stats |     23.5601 |      ms |
|                                   50th percentile service time |                    index-stats |     3.45235 |      ms |
|                                   90th percentile service time |                    index-stats |     4.21715 |      ms |
|                                   99th percentile service time |                    index-stats |     8.94257 |      ms |
|                                 99.9th percentile service time |                    index-stats |     18.5748 |      ms |
|                                  100th percentile service time |                    index-stats |     22.2653 |      ms |
|                                                     error rate |                    index-stats |           0 |       % |
|                                                 Min Throughput |                     node-stats |       89.18 |   ops/s |
|                                                Mean Throughput |                     node-stats |       89.69 |   ops/s |
|                                              Median Throughput |                     node-stats |       89.76 |   ops/s |
|                                                 Max Throughput |                     node-stats |       89.86 |   ops/s |
|                                        50th percentile latency |                     node-stats |     6.38122 |      ms |
|                                        90th percentile latency |                     node-stats |      8.6586 |      ms |
|                                        99th percentile latency |                     node-stats |     49.0793 |      ms |
|                                      99.9th percentile latency |                     node-stats |     65.1394 |      ms |
|                                       100th percentile latency |                     node-stats |     65.2263 |      ms |
|                                   50th percentile service time |                     node-stats |     5.47005 |      ms |
|                                   90th percentile service time |                     node-stats |     6.54033 |      ms |
|                                   99th percentile service time |                     node-stats |       12.86 |      ms |
|                                 99.9th percentile service time |                     node-stats |     22.4305 |      ms |
|                                  100th percentile service time |                     node-stats |     28.4076 |      ms |
|                                                     error rate |                     node-stats |           0 |       % |
|                                                 Min Throughput |                        default |       49.43 |   ops/s |
|                                                Mean Throughput |                        default |       49.67 |   ops/s |
|                                              Median Throughput |                        default |        49.7 |   ops/s |
|                                                 Max Throughput |                        default |       49.79 |   ops/s |
|                                        50th percentile latency |                        default |     6.01718 |      ms |
|                                        90th percentile latency |                        default |     7.80393 |      ms |
|                                        99th percentile latency |                        default |     17.2051 |      ms |
|                                      99.9th percentile latency |                        default |      30.309 |      ms |
|                                       100th percentile latency |                        default |     35.8789 |      ms |
|                                   50th percentile service time |                        default |     4.97983 |      ms |
|                                   90th percentile service time |                        default |     6.12833 |      ms |
|                                   99th percentile service time |                        default |     15.5193 |      ms |
|                                 99.9th percentile service time |                        default |     26.4137 |      ms |
|                                  100th percentile service time |                        default |     34.7689 |      ms |
|                                                     error rate |                        default |           0 |       % |
|                                                 Min Throughput |                           term |       95.39 |   ops/s |
|                                                Mean Throughput |                           term |       96.99 |   ops/s |
|                                              Median Throughput |                           term |       97.08 |   ops/s |
|                                                 Max Throughput |                           term |       98.16 |   ops/s |
|                                        50th percentile latency |                           term |     6.50646 |      ms |
|                                        90th percentile latency |                           term |      23.315 |      ms |
|                                        99th percentile latency |                           term |     164.069 |      ms |
|                                      99.9th percentile latency |                           term |     194.894 |      ms |
|                                       100th percentile latency |                           term |     198.846 |      ms |
|                                   50th percentile service time |                           term |     5.55759 |      ms |
|                                   90th percentile service time |                           term |     7.03259 |      ms |
|                                   99th percentile service time |                           term |     18.4044 |      ms |
|                                 99.9th percentile service time |                           term |      49.074 |      ms |
|                                  100th percentile service time |                           term |      183.66 |      ms |
|                                                     error rate |                           term |           0 |       % |
|                                                 Min Throughput |                         phrase |        66.7 |   ops/s |
|                                                Mean Throughput |                         phrase |        87.7 |   ops/s |
|                                              Median Throughput |                         phrase |       92.14 |   ops/s |
|                                                 Max Throughput |                         phrase |       97.01 |   ops/s |
|                                        50th percentile latency |                         phrase |     188.765 |      ms |
|                                        90th percentile latency |                         phrase |     1195.79 |      ms |
|                                        99th percentile latency |                         phrase |     1413.14 |      ms |
|                                      99.9th percentile latency |                         phrase |     1425.17 |      ms |
|                                       100th percentile latency |                         phrase |     1427.95 |      ms |
|                                   50th percentile service time |                         phrase |     5.19728 |      ms |
|                                   90th percentile service time |                         phrase |     7.11094 |      ms |
|                                   99th percentile service time |                         phrase |     19.8968 |      ms |
|                                 99.9th percentile service time |                         phrase |     43.0747 |      ms |
|                                  100th percentile service time |                         phrase |     45.1711 |      ms |
|                                                     error rate |                         phrase |           0 |       % |
|                                                 Min Throughput |           country_agg_uncached |        2.93 |   ops/s |
|                                                Mean Throughput |           country_agg_uncached |        2.94 |   ops/s |
|                                              Median Throughput |           country_agg_uncached |        2.94 |   ops/s |
|                                                 Max Throughput |           country_agg_uncached |        2.95 |   ops/s |
|                                        50th percentile latency |           country_agg_uncached |      168.53 |      ms |
|                                        90th percentile latency |           country_agg_uncached |     221.516 |      ms |
|                                        99th percentile latency |           country_agg_uncached |     302.165 |      ms |
|                                       100th percentile latency |           country_agg_uncached |     315.132 |      ms |
|                                   50th percentile service time |           country_agg_uncached |     167.622 |      ms |
|                                   90th percentile service time |           country_agg_uncached |     219.838 |      ms |
|                                   99th percentile service time |           country_agg_uncached |     300.684 |      ms |
|                                  100th percentile service time |           country_agg_uncached |     314.073 |      ms |
|                                                     error rate |           country_agg_uncached |           0 |       % |
|                                                 Min Throughput |             country_agg_cached |       97.77 |   ops/s |
|                                                Mean Throughput |             country_agg_cached |       98.37 |   ops/s |
|                                              Median Throughput |             country_agg_cached |       98.42 |   ops/s |
|                                                 Max Throughput |             country_agg_cached |       98.78 |   ops/s |
|                                        50th percentile latency |             country_agg_cached |     4.20455 |      ms |
|                                        90th percentile latency |             country_agg_cached |      5.4268 |      ms |
|                                        99th percentile latency |             country_agg_cached |     23.0755 |      ms |
|                                      99.9th percentile latency |             country_agg_cached |     34.3406 |      ms |
|                                       100th percentile latency |             country_agg_cached |      34.834 |      ms |
|                                   50th percentile service time |             country_agg_cached |     3.27497 |      ms |
|                                   90th percentile service time |             country_agg_cached |     4.22224 |      ms |
|                                   99th percentile service time |             country_agg_cached |      9.2231 |      ms |
|                                 99.9th percentile service time |             country_agg_cached |     33.0494 |      ms |
|                                  100th percentile service time |             country_agg_cached |     33.6098 |      ms |
|                                                     error rate |             country_agg_cached |           0 |       % |
|                                                 Min Throughput |                         scroll |       20.02 | pages/s |
|                                                Mean Throughput |                         scroll |       20.02 | pages/s |
|                                              Median Throughput |                         scroll |       20.02 | pages/s |
|                                                 Max Throughput |                         scroll |       20.02 | pages/s |
|                                        50th percentile latency |                         scroll |     373.196 |      ms |
|                                        90th percentile latency |                         scroll |     431.106 |      ms |
|                                        99th percentile latency |                         scroll |     465.907 |      ms |
|                                       100th percentile latency |                         scroll |     471.432 |      ms |
|                                   50th percentile service time |                         scroll |     369.894 |      ms |
|                                   90th percentile service time |                         scroll |     428.577 |      ms |
|                                   99th percentile service time |                         scroll |     462.544 |      ms |
|                                  100th percentile service time |                         scroll |     468.588 |      ms |
|                                                     error rate |                         scroll |           0 |       % |
|                                                 Min Throughput |                     expression |        1.49 |   ops/s |
|                                                Mean Throughput |                     expression |        1.49 |   ops/s |
|                                              Median Throughput |                     expression |        1.49 |   ops/s |
|                                                 Max Throughput |                     expression |        1.49 |   ops/s |
|                                        50th percentile latency |                     expression |     411.617 |      ms |
|                                        90th percentile latency |                     expression |     542.387 |      ms |
|                                        99th percentile latency |                     expression |     594.988 |      ms |
|                                       100th percentile latency |                     expression |     628.781 |      ms |
|                                   50th percentile service time |                     expression |     410.355 |      ms |
|                                   90th percentile service time |                     expression |     540.096 |      ms |
|                                   99th percentile service time |                     expression |     594.238 |      ms |
|                                  100th percentile service time |                     expression |     625.984 |      ms |
|                                                     error rate |                     expression |           0 |       % |
|                                                 Min Throughput |                painless_static |        1.39 |   ops/s |
|                                                Mean Throughput |                painless_static |        1.39 |   ops/s |
|                                              Median Throughput |                painless_static |        1.39 |   ops/s |
|                                                 Max Throughput |                painless_static |         1.4 |   ops/s |
|                                        50th percentile latency |                painless_static |     509.993 |      ms |
|                                        90th percentile latency |                painless_static |     553.665 |      ms |
|                                        99th percentile latency |                painless_static |     577.406 |      ms |
|                                       100th percentile latency |                painless_static |     592.807 |      ms |
|                                   50th percentile service time |                painless_static |     508.637 |      ms |
|                                   90th percentile service time |                painless_static |     552.225 |      ms |
|                                   99th percentile service time |                painless_static |     575.673 |      ms |
|                                  100th percentile service time |                painless_static |     591.699 |      ms |
|                                                     error rate |                painless_static |           0 |       % |
|                                                 Min Throughput |               painless_dynamic |         1.4 |   ops/s |
|                                                Mean Throughput |               painless_dynamic |         1.4 |   ops/s |
|                                              Median Throughput |               painless_dynamic |         1.4 |   ops/s |
|                                                 Max Throughput |               painless_dynamic |         1.4 |   ops/s |
|                                        50th percentile latency |               painless_dynamic |     516.665 |      ms |
|                                        90th percentile latency |               painless_dynamic |     542.619 |      ms |
|                                        99th percentile latency |               painless_dynamic |     568.623 |      ms |
|                                       100th percentile latency |               painless_dynamic |     589.562 |      ms |
|                                   50th percentile service time |               painless_dynamic |     515.552 |      ms |
|                                   90th percentile service time |               painless_dynamic |     541.262 |      ms |
|                                   99th percentile service time |               painless_dynamic |     567.652 |      ms |
|                                  100th percentile service time |               painless_dynamic |     587.972 |      ms |
|                                                     error rate |               painless_dynamic |           0 |       % |
|                                                 Min Throughput | decay_geo_gauss_function_score |           1 |   ops/s |
|                                                Mean Throughput | decay_geo_gauss_function_score |           1 |   ops/s |
|                                              Median Throughput | decay_geo_gauss_function_score |           1 |   ops/s |
|                                                 Max Throughput | decay_geo_gauss_function_score |           1 |   ops/s |
|                                        50th percentile latency | decay_geo_gauss_function_score |     452.763 |      ms |
|                                        90th percentile latency | decay_geo_gauss_function_score |     470.434 |      ms |
|                                        99th percentile latency | decay_geo_gauss_function_score |     494.168 |      ms |
|                                       100th percentile latency | decay_geo_gauss_function_score |     514.507 |      ms |
|                                   50th percentile service time | decay_geo_gauss_function_score |      450.98 |      ms |
|                                   90th percentile service time | decay_geo_gauss_function_score |     468.489 |      ms |
|                                   99th percentile service time | decay_geo_gauss_function_score |       493.1 |      ms |
|                                  100th percentile service time | decay_geo_gauss_function_score |     512.694 |      ms |
|                                                     error rate | decay_geo_gauss_function_score |           0 |       % |
|                                                 Min Throughput |   decay_geo_gauss_script_score |           1 |   ops/s |
|                                                Mean Throughput |   decay_geo_gauss_script_score |           1 |   ops/s |
|                                              Median Throughput |   decay_geo_gauss_script_score |           1 |   ops/s |
|                                                 Max Throughput |   decay_geo_gauss_script_score |           1 |   ops/s |
|                                        50th percentile latency |   decay_geo_gauss_script_score |     469.318 |      ms |
|                                        90th percentile latency |   decay_geo_gauss_script_score |     498.131 |      ms |
|                                        99th percentile latency |   decay_geo_gauss_script_score |     507.932 |      ms |
|                                       100th percentile latency |   decay_geo_gauss_script_score |      513.05 |      ms |
|                                   50th percentile service time |   decay_geo_gauss_script_score |     467.622 |      ms |
|                                   90th percentile service time |   decay_geo_gauss_script_score |     496.578 |      ms |
|                                   99th percentile service time |   decay_geo_gauss_script_score |     506.633 |      ms |
|                                  100th percentile service time |   decay_geo_gauss_script_score |     511.733 |      ms |
|                                                     error rate |   decay_geo_gauss_script_score |           0 |       % |
|                                                 Min Throughput |     field_value_function_score |         1.5 |   ops/s |
|                                                Mean Throughput |     field_value_function_score |         1.5 |   ops/s |
|                                              Median Throughput |     field_value_function_score |         1.5 |   ops/s |
|                                                 Max Throughput |     field_value_function_score |         1.5 |   ops/s |
|                                        50th percentile latency |     field_value_function_score |     163.418 |      ms |
|                                        90th percentile latency |     field_value_function_score |     191.239 |      ms |
|                                        99th percentile latency |     field_value_function_score |     225.152 |      ms |
|                                       100th percentile latency |     field_value_function_score |     225.597 |      ms |
|                                   50th percentile service time |     field_value_function_score |     162.158 |      ms |
|                                   90th percentile service time |     field_value_function_score |     189.522 |      ms |
|                                   99th percentile service time |     field_value_function_score |     223.846 |      ms |
|                                  100th percentile service time |     field_value_function_score |     223.876 |      ms |
|                                                     error rate |     field_value_function_score |           0 |       % |
|                                                 Min Throughput |       field_value_script_score |         1.5 |   ops/s |
|                                                Mean Throughput |       field_value_script_score |         1.5 |   ops/s |
|                                              Median Throughput |       field_value_script_score |         1.5 |   ops/s |
|                                                 Max Throughput |       field_value_script_score |         1.5 |   ops/s |
|                                        50th percentile latency |       field_value_script_score |       239.9 |      ms |
|                                        90th percentile latency |       field_value_script_score |      261.97 |      ms |
|                                        99th percentile latency |       field_value_script_score |     323.172 |      ms |
|                                       100th percentile latency |       field_value_script_score |     330.068 |      ms |
|                                   50th percentile service time |       field_value_script_score |     238.426 |      ms |
|                                   90th percentile service time |       field_value_script_score |     260.274 |      ms |
|                                   99th percentile service time |       field_value_script_score |     321.688 |      ms |
|                                  100th percentile service time |       field_value_script_score |     327.831 |      ms |
|                                                     error rate |       field_value_script_score |           0 |       % |
|                                                 Min Throughput |                    large_terms |         0.9 |   ops/s |
|                                                Mean Throughput |                    large_terms |        0.91 |   ops/s |
|                                              Median Throughput |                    large_terms |        0.91 |   ops/s |
|                                                 Max Throughput |                    large_terms |        0.92 |   ops/s |
|                                        50th percentile latency |                    large_terms |     50382.2 |      ms |
|                                        90th percentile latency |                    large_terms |       51336 |      ms |
|                                        99th percentile latency |                    large_terms |     51455.8 |      ms |
|                                       100th percentile latency |                    large_terms |     51498.7 |      ms |
|                                   50th percentile service time |                    large_terms |      1037.9 |      ms |
|                                   90th percentile service time |                    large_terms |     1265.36 |      ms |
|                                   99th percentile service time |                    large_terms |     1425.96 |      ms |
|                                  100th percentile service time |                    large_terms |     1445.15 |      ms |
|                                                     error rate |                    large_terms |           0 |       % |
|                                                 Min Throughput |           large_filtered_terms |        1.06 |   ops/s |
|                                                Mean Throughput |           large_filtered_terms |        1.06 |   ops/s |
|                                              Median Throughput |           large_filtered_terms |        1.06 |   ops/s |
|                                                 Max Throughput |           large_filtered_terms |        1.06 |   ops/s |
|                                        50th percentile latency |           large_filtered_terms |     9157.42 |      ms |
|                                        90th percentile latency |           large_filtered_terms |     9566.33 |      ms |
|                                        99th percentile latency |           large_filtered_terms |     9736.84 |      ms |
|                                       100th percentile latency |           large_filtered_terms |     9747.07 |      ms |
|                                   50th percentile service time |           large_filtered_terms |     912.114 |      ms |
|                                   90th percentile service time |           large_filtered_terms |      1030.6 |      ms |
|                                   99th percentile service time |           large_filtered_terms |     1107.59 |      ms |
|                                  100th percentile service time |           large_filtered_terms |     1119.17 |      ms |
|                                                     error rate |           large_filtered_terms |           0 |       % |
|                                                 Min Throughput |         large_prohibited_terms |        1.09 |   ops/s |
|                                                Mean Throughput |         large_prohibited_terms |        1.09 |   ops/s |
|                                              Median Throughput |         large_prohibited_terms |        1.09 |   ops/s |
|                                                 Max Throughput |         large_prohibited_terms |         1.1 |   ops/s |
|                                        50th percentile latency |         large_prohibited_terms |     1911.18 |      ms |
|                                        90th percentile latency |         large_prohibited_terms |     2454.98 |      ms |
|                                        99th percentile latency |         large_prohibited_terms |     2584.01 |      ms |
|                                       100th percentile latency |         large_prohibited_terms |     2588.84 |      ms |
|                                   50th percentile service time |         large_prohibited_terms |     877.527 |      ms |
|                                   90th percentile service time |         large_prohibited_terms |     1007.55 |      ms |
|                                   99th percentile service time |         large_prohibited_terms |     1081.14 |      ms |
|                                  100th percentile service time |         large_prohibited_terms |     1119.93 |      ms |
|                                                     error rate |         large_prohibited_terms |           0 |       % |
|                                                 Min Throughput |           desc_sort_population |        1.49 |   ops/s |
|                                                Mean Throughput |           desc_sort_population |         1.5 |   ops/s |
|                                              Median Throughput |           desc_sort_population |         1.5 |   ops/s |
|                                                 Max Throughput |           desc_sort_population |         1.5 |   ops/s |
|                                        50th percentile latency |           desc_sort_population |     86.1424 |      ms |
|                                        90th percentile latency |           desc_sort_population |     108.048 |      ms |
|                                        99th percentile latency |           desc_sort_population |     135.423 |      ms |
|                                       100th percentile latency |           desc_sort_population |     170.145 |      ms |
|                                   50th percentile service time |           desc_sort_population |     84.2094 |      ms |
|                                   90th percentile service time |           desc_sort_population |     106.695 |      ms |
|                                   99th percentile service time |           desc_sort_population |     133.797 |      ms |
|                                  100th percentile service time |           desc_sort_population |     167.791 |      ms |
|                                                     error rate |           desc_sort_population |           0 |       % |
|                                                 Min Throughput |            asc_sort_population |         1.5 |   ops/s |
|                                                Mean Throughput |            asc_sort_population |        1.51 |   ops/s |
|                                              Median Throughput |            asc_sort_population |        1.51 |   ops/s |
|                                                 Max Throughput |            asc_sort_population |        1.51 |   ops/s |
|                                        50th percentile latency |            asc_sort_population |     86.3175 |      ms |
|                                        90th percentile latency |            asc_sort_population |     105.639 |      ms |
|                                        99th percentile latency |            asc_sort_population |     139.911 |      ms |
|                                       100th percentile latency |            asc_sort_population |     143.371 |      ms |
|                                   50th percentile service time |            asc_sort_population |     84.7843 |      ms |
|                                   90th percentile service time |            asc_sort_population |     104.182 |      ms |
|                                   99th percentile service time |            asc_sort_population |      137.07 |      ms |
|                                  100th percentile service time |            asc_sort_population |      140.65 |      ms |
|                                                     error rate |            asc_sort_population |           0 |       % |
|                                                 Min Throughput | asc_sort_with_after_population |         1.5 |   ops/s |
|                                                Mean Throughput | asc_sort_with_after_population |         1.5 |   ops/s |
|                                              Median Throughput | asc_sort_with_after_population |         1.5 |   ops/s |
|                                                 Max Throughput | asc_sort_with_after_population |         1.5 |   ops/s |
|                                        50th percentile latency | asc_sort_with_after_population |     119.115 |      ms |
|                                        90th percentile latency | asc_sort_with_after_population |     137.756 |      ms |
|                                        99th percentile latency | asc_sort_with_after_population |     170.733 |      ms |
|                                       100th percentile latency | asc_sort_with_after_population |     179.635 |      ms |
|                                   50th percentile service time | asc_sort_with_after_population |     117.399 |      ms |
|                                   90th percentile service time | asc_sort_with_after_population |      136.08 |      ms |
|                                   99th percentile service time | asc_sort_with_after_population |     169.046 |      ms |
|                                  100th percentile service time | asc_sort_with_after_population |     177.991 |      ms |
|                                                     error rate | asc_sort_with_after_population |           0 |       % |
|                                                 Min Throughput |            desc_sort_geonameid |        5.92 |   ops/s |
|                                                Mean Throughput |            desc_sort_geonameid |        5.94 |   ops/s |
|                                              Median Throughput |            desc_sort_geonameid |        5.94 |   ops/s |
|                                                 Max Throughput |            desc_sort_geonameid |        5.95 |   ops/s |
|                                        50th percentile latency |            desc_sort_geonameid |     22.8417 |      ms |
|                                        90th percentile latency |            desc_sort_geonameid |      27.063 |      ms |
|                                        99th percentile latency |            desc_sort_geonameid |     37.5493 |      ms |
|                                       100th percentile latency |            desc_sort_geonameid |     37.6269 |      ms |
|                                   50th percentile service time |            desc_sort_geonameid |      21.266 |      ms |
|                                   90th percentile service time |            desc_sort_geonameid |     25.3401 |      ms |
|                                   99th percentile service time |            desc_sort_geonameid |     36.0571 |      ms |
|                                  100th percentile service time |            desc_sort_geonameid |     36.9911 |      ms |
|                                                     error rate |            desc_sort_geonameid |           0 |       % |
|                                                 Min Throughput | desc_sort_with_after_geonameid |        5.94 |   ops/s |
|                                                Mean Throughput | desc_sort_with_after_geonameid |        5.95 |   ops/s |
|                                              Median Throughput | desc_sort_with_after_geonameid |        5.95 |   ops/s |
|                                                 Max Throughput | desc_sort_with_after_geonameid |        5.96 |   ops/s |
|                                        50th percentile latency | desc_sort_with_after_geonameid |     116.962 |      ms |
|                                        90th percentile latency | desc_sort_with_after_geonameid |      137.13 |      ms |
|                                        99th percentile latency | desc_sort_with_after_geonameid |      149.02 |      ms |
|                                       100th percentile latency | desc_sort_with_after_geonameid |     154.085 |      ms |
|                                   50th percentile service time | desc_sort_with_after_geonameid |     116.277 |      ms |
|                                   90th percentile service time | desc_sort_with_after_geonameid |     136.257 |      ms |
|                                   99th percentile service time | desc_sort_with_after_geonameid |     148.259 |      ms |
|                                  100th percentile service time | desc_sort_with_after_geonameid |     152.529 |      ms |
|                                                     error rate | desc_sort_with_after_geonameid |           0 |       % |
|                                                 Min Throughput |             asc_sort_geonameid |           6 |   ops/s |
|                                                Mean Throughput |             asc_sort_geonameid |           6 |   ops/s |
|                                              Median Throughput |             asc_sort_geonameid |           6 |   ops/s |
|                                                 Max Throughput |             asc_sort_geonameid |           6 |   ops/s |
|                                        50th percentile latency |             asc_sort_geonameid |     13.5861 |      ms |
|                                        90th percentile latency |             asc_sort_geonameid |     15.6207 |      ms |
|                                        99th percentile latency |             asc_sort_geonameid |     40.4421 |      ms |
|                                       100th percentile latency |             asc_sort_geonameid |      58.184 |      ms |
|                                   50th percentile service time |             asc_sort_geonameid |      12.471 |      ms |
|                                   90th percentile service time |             asc_sort_geonameid |     14.3571 |      ms |
|                                   99th percentile service time |             asc_sort_geonameid |     38.8471 |      ms |
|                                  100th percentile service time |             asc_sort_geonameid |     56.6552 |      ms |
|                                                     error rate |             asc_sort_geonameid |           0 |       % |
|                                                 Min Throughput |  asc_sort_with_after_geonameid |           6 |   ops/s |
|                                                Mean Throughput |  asc_sort_with_after_geonameid |        6.01 |   ops/s |
|                                              Median Throughput |  asc_sort_with_after_geonameid |        6.01 |   ops/s |
|                                                 Max Throughput |  asc_sort_with_after_geonameid |        6.01 |   ops/s |
|                                        50th percentile latency |  asc_sort_with_after_geonameid |     91.6348 |      ms |
|                                        90th percentile latency |  asc_sort_with_after_geonameid |     109.754 |      ms |
|                                        99th percentile latency |  asc_sort_with_after_geonameid |     154.618 |      ms |
|                                       100th percentile latency |  asc_sort_with_after_geonameid |     192.748 |      ms |
|                                   50th percentile service time |  asc_sort_with_after_geonameid |      90.231 |      ms |
|                                   90th percentile service time |  asc_sort_with_after_geonameid |     106.687 |      ms |
|                                   99th percentile service time |  asc_sort_with_after_geonameid |     152.959 |      ms |
|                                  100th percentile service time |  asc_sort_with_after_geonameid |     190.269 |      ms |
|                                                     error rate |  asc_sort_with_after_geonameid |           0 |       % |


----------------------------------
[INFO] SUCCESS (took 4702 seconds)
----------------------------------