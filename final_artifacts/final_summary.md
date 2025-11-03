# Mall Customers — Final Clustering Summary
- Previous BEST: **birch** — Silhouette: 0.5366
- Final-k: **kmeans** (k=3)

## Cluster Sizes — Previous
```
           Count
Cluster         
Cluster 0     42
Cluster 1     14
Cluster 2      1
Cluster 3    383
```

## Numeric Profiles (means) — Previous
```
              fresh      milk   grocery    frozen  detergents_paper  delicassen
Cluster                                                                        
Cluster 0   7562.02  18520.88  29017.88   1739.67          14006.43     1971.52
Cluster 1  50395.07   8900.21   9627.21  14678.14           1705.07     5479.57
Cluster 2  36847.00  43950.00  20170.00  36534.00            239.00    47943.00
Cluster 3  11018.66   4187.80   5547.94   2706.41           1711.43     1210.14
```

## Cluster Sizes — Final-k
```
           Count
Cluster         
Cluster 0    350
Cluster 1     53
Cluster 2     37
```

## Numeric Profiles (means) — Final-k
```
              fresh      milk   grocery   frozen  detergents_paper  delicassen
Cluster                                                                       
Cluster 0   8935.50   4228.53   5848.03  2167.23           1913.61     1102.12
Cluster 1  34540.11   5860.36   6122.62  9841.74            981.47     3664.25
Cluster 2   8704.86  20534.41  30466.24  1932.62          14758.84     2459.35
```

## Prev → Final-k Label Mapping
```
           final_label
prev_label            
Cluster 3    Cluster 0
Cluster 0    Cluster 2
Cluster 1    Cluster 1
```

_Generated: 2025-11-02T16:00:17_