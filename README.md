# TopologyBench

**TopologyBench standardises research on core optical networks.**

## Real World Topology

<!---
| Real World Topology | Topology (Nodes, Edges) | Simulated Traffic (Type 1, 2, 3) | Visualisation         | Download |
|---------------------|-------------------------|----------------------------------|-----------------------|----------|
| Network 1           | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)       | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)              | [zipped(.png, html)](https://github.com/TopologyBench/TopologyBench.github.io) | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
| Network .. N        | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)       | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)              | [zipped(.png, html)](https://github.com/TopologyBench/TopologyBench.github.io) | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
| **Download All**    |                         |                                  |                       | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
--->


| No. | Topology Name        | Nodes | Edges | Average Node Degree | Diameter (Hops) | Average Link Length (km) | Algebraic Connectivity | Region            | Category Name | Survivable     |
|-----|----------------------|-------|-------|---------------------|-----------------|--------------------------|------------------------|-------------------|---------------|----------------|
|   1 | ABILENE              |    11 |    14 |                2.55 |               5 |                  1353.28 |                   0.13 | USA               | Class 2       | survivable     |
|   2 | ANS                  |    18 |    25 |                2.78 |               6 |                  1358.61 |                   0.07 | USA               | Class 3       | non-survivable |
|   3 | ARNES                |    17 |    20 |                2.35 |               6 |                    51.55 |                    0.1 | Slovenia          | Class 3       | survivable     |
|   4 | ARPANET              |    20 |    32 |                 3.2 |               6 |                  1173.06 |                    0.1 | USA               | Class 3       | survivable     |
|   5 | ATMNET               |    21 |    22 |                 2.1 |               9 |                   826.88 |                   0.05 | USA               | Class 1       | non-survivable |
|   6 | BBNPLANET            |    27 |    28 |                2.07 |               7 |                   853.54 |                   0.03 | USA               | Class 3       | non-survivable |
|   7 | BEYONDTHENETWORK     |    29 |    41 |                2.83 |               6 |                   888.67 |                   0.05 | USA               | Class 3       | non-survivable |
|   8 | BICS                 |    33 |    48 |                2.91 |               8 |                   610.97 |                   0.04 | Europe            | Class 3       | non-survivable |
|   9 | BIZNET               |    28 |    32 |                2.29 |              15 |                   155.34 |                   0.01 | Indonesia         | Class 1       | non-survivable |
|  10 | BREN                 |    10 |    11 |                 2.2 |               4 |                   170.27 |                   0.17 | Bulgaria          | Class 2       | survivable     |
|  11 | CANARIE19            |    19 |    26 |                2.74 |               7 |                   923.11 |                   0.08 | Canada/USA        | Class 3       | survivable     |
|  12 | CANARIE24            |    24 |    33 |                2.75 |               7 |                   966.22 |                  0.051 | Canada/USA        | Class 3       | non-survivable |
|  13 | CERNET               |    36 |    51 |                2.83 |               5 |                   855.46 |                   0.08 | China             | Class 3       | non-survivable |
|  14 | CESNET               |    12 |    19 |                3.17 |               4 |                   136.97 |                    0.2 | China             | Class 3       | survivable     |
|  15 | CLARANET             |    15 |    18 |                 2.4 |               4 |                   659.69 |                   0.25 | Europe            | Class 3       | non-survivable |
|  16 | CONUS100             |   100 |   136 |                2.72 |              15 |                  1380.74 |                   0.02 | USA               | Class 1       | survivable     |
|  17 | CONUS30              |    30 |    36 |                 2.4 |              11 |                   780.28 |                   0.03 | USA               | Class 1       | survivable     |
|  18 | CONUS6077            |    60 |    77 |                2.57 |              14 |                      521 |                   0.02 | USA               | Class 1       | survivable     |
|  19 | CONUS6079            |    60 |    79 |                2.63 |              15 |                   543.87 |                   0.02 | USA               | Class 1       | survivable     |
|  20 | CONUS75              |    75 |    99 |                2.64 |              17 |                   494.35 |                   0.01 | USA               | Class 1       | survivable     |
|  21 | CORONET              |    60 |    79 |                2.63 |              15 |                   543.87 |                   0.02 | USA               | Class 1       | survivable     |
|  22 | COST                 |    37 |    57 |                3.08 |               8 |                   648.17 |                   0.04 | Europe            | Class 3       | survivable     |
|  23 | CRLNETWORKSERVICES   |    33 |    38 |                 2.3 |              10 |                   924.96 |                   0.02 | USA               | Class 1       | non-survivable |
|  24 | CWIX                 |    23 |    29 |                2.52 |               7 |                   922.32 |                   0.07 | USA               | Class 3       | non-survivable |
|  25 | DARKSTRAND           |    28 |    31 |                2.21 |              11 |                    681.4 |                   0.04 | USA               | Class 1       | survivable     |
|  26 | DIGEX                |    31 |    35 |                2.26 |              10 |                    803.3 |                   0.04 | USA               | Class 1       | survivable     |
|  27 | DT17                 |    14 |    22 |                3.14 |               5 |                   185.58 |                    0.2 | Germany           | Class 3       | survivable     |
|  28 | ELIBACKBONE          |    20 |    30 |                   3 |               6 |                   1056.6 |                    0.1 | USA               | Class 3       | survivable     |
|  29 | EON                  |    19 |    37 |                3.89 |               5 |                   918.67 |                   0.14 | Europe            | Class 3       | survivable     |
|  30 | EPOCH                |     6 |     7 |                2.33 |               3 |                  2277.42 |                   0.27 | USA               | Class 2       | survivable     |
|  31 | ERNET                |    16 |    18 |                2.25 |               4 |                   897.72 |                   0.19 | India             | Class 3       | non-survivable |
|  32 | FUNET                |    24 |    27 |                2.25 |               9 |                   157.81 |                   0.06 | Finland           | Class 1       | non-survivable |
|  33 | GAMBIA               |    12 |    12 |                   2 |               5 |                    61.57 |                    0.1 | Gambia            | Class 2       | non-survivable |
|  34 | GBLNET               |     8 |     7 |                1.75 |               4 |                   818.59 |                   0.27 | Europe            | Class 2       | non-survivable |
|  35 | GEANT                |    22 |    36 |                3.27 |               5 |                  1388.75 |                   0.15 | Inter-Continental | Class 3       | survivable     |
|  36 | GEANT2               |    35 |    55 |                3.14 |               8 |                   881.15 |                   0.07 | Europe            | Class 3       | survivable     |
|  37 | GERMANY50            |    50 |    88 |                3.52 |               9 |                   193.14 |                   0.05 | Germany           | Class 3       | survivable     |
|  38 | GETNET               |     7 |     8 |                2.29 |               3 |                  2146.64 |                   0.57 | USA               | Class 2       | non-survivable |
|  39 | GRNET                |    34 |    39 |                2.29 |               8 |                   190.21 |                   0.14 | Greece            | Class 3       | non-survivable |
|  40 | GTSCZECHREPUBLIC     |    26 |    25 |                1.92 |              17 |                    92.29 |                   0.01 | Czech Republic    | Class 1       | non-survivable |
|  41 | GTSPOLAND            |    26 |    28 |                2.15 |              12 |                   154.73 |                   0.05 | Poland            | Class 1       | non-survivable |
|  42 | HIBERNIACANADA       |    10 |    10 |                   2 |               7 |                  1615.95 |                   0.07 | Canada            | Class 2       | non-survivable |
|  43 | HIBERNIAGLOBAL       |    53 |    76 |                2.87 |              18 |                   719.31 |                   0.01 | Global            | Class 1       | non-survivable |
|  44 | HIBERNIAIRELAND      |     6 |     6 |                   2 |               3 |                   142.22 |                   0.43 | Ireland           | Class 1       | non-survivable |
|  45 | HIBERNIANIRELAND     |    15 |    16 |                2.13 |              10 |                    64.05 |                   0.02 | Ireland           | Class 2       | non-survivable |
|  46 | HIBERNIAUK           |    13 |    13 |                   2 |               6 |                   104.95 |                   0.08 | UK                | Class 2       | survivable     |
|  47 | HIBERNIAUS           |    20 |    27 |                 2.7 |              10 |                    405.3 |                   0.01 | USA               | Class 1       | non-survivable |
|  48 | HOSTWAYINTERNATIONAL |    16 |    21 |                2.63 |               8 |                  4159.84 |                   0.05 | Global            | Class 3       | non-survivable |
|  49 | IBM                  |    18 |    24 |                2.67 |               6 |                  1258.93 |                   0.07 | USA               | Class 3       | non-survivable |
|  50 | INTEGRA              |    27 |    36 |                2.67 |               7 |                   757.45 |                   0.09 | USA               | Class 3       | non-survivable |
|  51 | IRIS                 |    50 |    64 |                2.56 |              10 |                    94.34 |                   0.03 | USA               | Class 1       | non-survivable |
|  52 | ISTAR                |    19 |    19 |                   2 |               7 |                   696.54 |                   0.07 | Canada            | Class 1       | non-survivable |
|  53 | ITALY                |    21 |    35 |                3.33 |               7 |                   271.16 |                   0.07 | Italy             | Class 3       | survivable     |
|  54 | JANOSUS              |    26 |    42 |                3.23 |               8 |                   882.12 |                   0.08 | USA               | Class 3       | survivable     |
|  55 | JGN2PLUS             |    11 |    10 |                1.82 |               7 |                   598.39 |                   0.03 | Japan             | Class 2       | non-survivable |
|  56 | JPN12                |    12 |    17 |                2.83 |               5 |                   623.44 |                   0.09 | Japan             | Class 3       | survivable     |
|  57 | JPN25                |    25 |    43 |                3.44 |               8 |                    318.7 |                   0.03 | Japan             | Class 3       | survivable     |
|  58 | JPN48                |    48 |    82 |                3.42 |              14 |                   230.69 |                   0.01 | Japan             | Class 1       | survivable     |
|  59 | KAREN                |    22 |    25 |                2.27 |               6 |                   145.81 |                   0.06 | New Zealand       | Class 3       | non-survivable |
|  60 | LAMBDARAIL           |    19 |    23 |                2.42 |               7 |                   907.53 |                   0.07 | USA               | Class 1       | survivable     |
|  61 | LAYER42              |     6 |     7 |                2.33 |               3 |                  2056.05 |                   0.73 | USA               | Class 2       | non-survivable |
|  62 | LONI                 |    32 |    36 |                2.25 |              12 |                    76.72 |                   0.03 | USA (Louisiana)   | Class 1       | survivable     |
|  63 | MARWAN               |     6 |     6 |                   2 |               3 |                   413.97 |                    0.3 | Morocco           | Class 2       | survivable     |
|  64 | MEMOREX              |    19 |    24 |                2.53 |               7 |                   205.93 |                   0.06 | Europe            | Class 3       | survivable     |
|  65 | METRONA              |    33 |    41 |                2.48 |              11 |                   640.21 |                   0.01 | UK                | Class 1       | survivable     |
|  66 | MZIMA                |    14 |    18 |                2.57 |               5 |                   1239.8 |                   0.11 | USA               | Class 3       | survivable     |
|  67 | NETRAIL              |     7 |    10 |                2.86 |               2 |                   1768.6 |                   0.36 | USA               | Class 2       | survivable     |
|  68 | NETWORKUSA           |    35 |    39 |                2.23 |              10 |                   130.86 |                   0.02 | USA               | Class 1       | non-survivable |
|  69 | NEWNET               |    26 |    31 |                2.38 |               9 |                    787.7 |                   0.05 | USA               | Class 1       | survivable     |
|  70 | NEXTGEN              |    16 |    16 |                   2 |              13 |                    661.5 |                   0.01 | Australia         | Class 1       | non-survivable |
|  71 | NOBELEU              |    28 |    41 |                2.93 |               8 |                   622.18 |                   0.05 | Europe            | Class 3       | survivable     |
|  72 | NOBELGERMANY         |    17 |    26 |                3.06 |               6 |                      215 |                   0.17 | Germany           | Class 3       | survivable     |
|  73 | NOBELUS              |    14 |    21 |                   3 |               3 |                  1464.78 |                   0.27 | USA               | Class 3       | survivable     |
|  74 | NOEL                 |    19 |    25 |                2.63 |               6 |                   157.52 |                   0.17 | USA               | Class 3       | non-survivable |
|  75 | NSFNET13             |    13 |    15 |                2.31 |               5 |                  1480.27 |                   0.22 | USA               | Class 3       | non-survivable |
|  76 | OPTUNETSWEDEN        |    25 |    29 |                2.32 |              12 |                   253.13 |                   0.03 | Sweden            | Class 1       | non-survivable |
|  77 | OXFORD               |    19 |    25 |                2.63 |               7 |                    81.52 |                   0.06 | USA               | Class 3       | survivable     |
|  78 | PACKETEXCHANGE       |    21 |    27 |                2.57 |               9 |                  3410.12 |                   0.02 | Global            | Class 1       | non-survivable |
|  79 | PALMETTO             |    45 |    64 |                2.84 |              12 |                   100.53 |                   0.03 | USA               | Class 1       | non-survivable |
|  80 | PIONIER              |    21 |    25 |                2.38 |               7 |                   183.21 |                   0.07 | Poland            | Class 3       | survivable     |
|  81 | PIONIERL3            |    27 |    32 |                2.37 |              10 |                   167.05 |                   0.04 | Poland            | Class 1       | non-survivable |
|  82 | POLSKA               |    12 |    18 |                   3 |               4 |                   282.11 |                   0.21 | Poland            | Class 3       | survivable     |
|  83 | PORTUGAL             |    26 |    36 |                2.77 |               8 |                   263.17 |                   0.04 | Portugal          | Class 3       | survivable     |
|  84 | PSINET               |    24 |    25 |                2.08 |              11 |                   769.97 |                   0.02 | USA               | Class 1       | non-survivable |
|  85 | RAILTELINDIA         |    19 |    28 |                2.95 |               6 |                   649.37 |                   0.18 | India             | Class 3       | survivable     |
|  86 | REDCLARA             |    14 |    17 |                2.43 |               4 |                   2717.7 |                   0.25 | South America     | Class 3       | non-survivable |
|  87 | REDIRIS              |    18 |    30 |                3.33 |               4 |                   506.26 |                    0.2 | Spain             | Class 3       | survivable     |
|  88 | RENATER              |    27 |    35 |                2.59 |               6 |                   231.56 |                   0.12 | France            | Class 3       | survivable     |
|  89 | RENATER1999          |    24 |    23 |                1.92 |               7 |                   289.84 |                   0.08 | France            | Class 3       | non-survivable |
|  90 | RENATER2001          |    24 |    27 |                2.25 |               6 |                   273.86 |                   0.13 | France            | Class 3       | non-survivable |
|  91 | RENATER2004          |    24 |    29 |                2.42 |               7 |                   269.53 |                   0.13 | France            | Class 3       | non-survivable |
|  92 | RENATER2006          |    26 |    34 |                2.62 |               7 |                   247.94 |                    0.1 | France            | Class 3       | non-survivable |
|  93 | RENATER2008          |    26 |    34 |                2.62 |               7 |                   247.94 |                    0.1 | France            | Class 3       | non-survivable |
|  94 | RENATER2010          |    37 |    48 |                2.59 |               9 |                   215.25 |                   0.07 | France            | Class 3       | non-survivable |
|  95 | RNPBRAZIL            |    10 |    12 |                 2.4 |               5 |                  1049.74 |                   0.18 | Brazil            | Class 2       | survivable     |
|  96 | SAGO                 |    18 |    17 |                1.89 |              14 |                   108.52 |                   0.02 | USA               | Class 1       | non-survivable |
|  97 | SANET                |    46 |    55 |                2.39 |              13 |                    32.53 |                   0.02 | Slovakia          | Class 1       | non-survivable |
|  98 | SANREN               |     7 |     7 |                   2 |               3 |                   692.31 |                   0.15 | South Africa      | Class 2       | survivable     |
|  99 | SAVVIS               |    19 |    20 |                2.11 |               8 |                   811.75 |                   0.04 | USA               | Class 1       | non-survivable |
| 100 | SPIRALIGHT           |    15 |    16 |                2.13 |               8 |                   132.21 |                   0.07 | USA               | Class 3       | survivable     |
| 101 | TATANID              |   142 |   180 |                2.54 |              28 |                   200.76 |                   0.01 | India             | Class 1       | non-survivable |
| 102 | TELECOMSERBIA        |     6 |     6 |                   2 |               3 |                   213.98 |                   0.29 | Serbia            | Class 2       | survivable     |
| 103 | UNIC                 |    15 |    17 |                2.27 |               8 |                    72.73 |                   0.04 | Denmark           | Class 1       | non-survivable |
| 104 | USA100               |   100 |   171 |                3.42 |              16 |                   411.74 |                   0.02 | USA               | Class 1       | survivable     |
| 105 | VIA                  |     9 |    12 |                2.67 |               4 |                   821.66 |                   0.27 | Europe            | Class 2       | survivabl      |



<!--
## Synthetic Topology

| Synthetic Topology  | Topology (Nodes, Edges) | Simulated Traffic (Type 1, 2, 3) | Visualisation         | Download |
|---------------------|-------------------------|----------------------------------|-----------------------|----------|
| Simple              | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)       | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)              | [zipped(.png, html)](https://github.com/TopologyBench/TopologyBench.github.io) | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
| Syn-small           | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)       | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)              | [zipped(.png, html)](https://github.com/TopologyBench/TopologyBench.github.io) | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
| Syn-large           | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)       | [zipped(.csv)](https://github.com/TopologyBench/TopologyBench.github.io)              | [zipped(.png, html)](https://github.com/TopologyBench/TopologyBench.github.io) | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |
| **Download All**    |                         |                                  |                       | [⬇](https://github.com/TopologyBench/TopologyBench.github.io)        |

--->

## Sponsored and Supported By
- University of Cambridge
- EPSRC
- UKRI
- British Telecommunications
- Google Generation Scholarship
- University College London
- TRANSNET

<!--
![University of Cambridge](UniversityOfCambridge.png)
![EPSRC](EPSRC.png)
![UKRI](UKRI.png)
![British Telecommunications](BritishTelecommunications.png)
![Google Generation Scholarship](GoogleGenerationScholarship.png)
![University College London](UniversityCollegeLondon.png)
![TRANSNET](TRANSNET.png)
-->
