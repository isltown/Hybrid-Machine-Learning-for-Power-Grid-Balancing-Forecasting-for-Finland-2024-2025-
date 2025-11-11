# Data Quality Report

**File**: `/kaggle/input/finland-afrr-energy-market-and-weather-data/extended_data_v2.csv`

- Rows: 6456
- Columns: 17


## Datetime index check

- Start: 2024-06-20 22:00:00+00:00
- End: 2025-03-16 22:00:00+00:00
- Rows (hours): 6456

- Missing hourly timestamps: 1

- Max gap (hours): 2.0


## Top nullable columns (by % missing)

|                                          |   pct_null |
|:-----------------------------------------|-----------:|
| Up                                       |          0 |
| Down                                     |          0 |
| sp                                       |          0 |
| cloud_amount                             |          0 |
| wind_speed                               |          0 |
| precipitation_amount                     |          0 |
| pressure                                 |          0 |
| air_temperature                          |          0 |
| relative_humidity                        |          0 |
| wind_direction                           |          0 |
| Down_Cap                                 |          0 |
| Up_Cap                                   |          0 |
| is_public_holiday                        |          0 |
| electricity_consumption                  |          0 |
| electricity_consumption_Finnish_networks |          0 |
| electricity_consumption_forecast         |          0 |

## Dtype table (sample)

|                                          | dtype               |   n_unique |   n_null |   pct_null |
|:-----------------------------------------|:--------------------|-----------:|---------:|-----------:|
| datetime                                 | datetime64[ns, UTC] |       6456 |        0 |          0 |
| Up                                       | float64             |       5289 |        0 |          0 |
| Down                                     | float64             |       5493 |        0 |          0 |
| sp                                       | float64             |       3898 |        0 |          0 |
| cloud_amount                             | float64             |       3117 |        0 |          0 |
| wind_speed                               | float64             |       5627 |        0 |          0 |
| precipitation_amount                     | float64             |        503 |        0 |          0 |
| pressure                                 | float64             |       6192 |        0 |          0 |
| air_temperature                          | float64             |       6118 |        0 |          0 |
| relative_humidity                        | float64             |       5085 |        0 |          0 |
| wind_direction                           | float64             |       6156 |        0 |          0 |
| Down_Cap                                 | float64             |       1238 |        0 |          0 |
| Up_Cap                                   | float64             |       1305 |        0 |          0 |
| is_public_holiday                        | int64               |          2 |        0 |          0 |
| electricity_consumption                  | float64             |       6423 |        0 |          0 |
| electricity_consumption_Finnish_networks | float64             |       6456 |        0 |          0 |
| electricity_consumption_forecast         | float64             |       6359 |        0 |          0 |

## Constant columns (no variability)

None

## Duplicates

- Duplicate rows (exact): 0


## Numeric summary (sample rows)

|                                          |   count |            mean |             std |            min |             25% |             50% |            75% |             max |    skew |   kurtosis |   n_inf_pos |   n_inf_neg |   n_zeros |
|:-----------------------------------------|--------:|----------------:|----------------:|---------------:|----------------:|----------------:|---------------:|----------------:|--------:|-----------:|------------:|------------:|----------:|
| Up                                       |    6456 |    92.9384      |    72.8664      |   -2.73        |    40.3244      |    66.05        |   135.763      |   635.4         |  1.4358 |     2.9468 |           0 |           0 |         0 |
| Down                                     |    6456 |    -7.19155     |    26.2335      | -219.81        |   -23.623       |    -9.39856     |     6.30375    |   136.01        |  0.6029 |     3.0747 |           0 |           0 |        14 |
| sp                                       |    6456 |    38.6125      |    54.5258      |  -20.01        |     3.23        |    19.14        |    50.47       |   500.08        |  2.5535 |     9.721  |           0 |           0 |       152 |
| cloud_amount                             |    6456 |     5.12243     |     2.51766     |    0           |     3.13333     |     5.8         |     7.39286    |     8.70238     | -0.5682 |    -1.0039 |           0 |           0 |        66 |
| wind_speed                               |    6456 |     3.47596     |     1.3802      |    0.883333    |     2.44774     |     3.24643     |     4.33233    |    10.1417      |  0.8063 |     0.5146 |           0 |           0 |         0 |
| precipitation_amount                     |    6456 |     0.081028    |     0.226117    |    0           |     0           |     0           |     0.0428571  |     3.69333     |  6.273  |    60.8811 |           0 |           0 |      3953 |
| pressure                                 |    6456 |  1012.13        |    12.2772      |  977.119       |  1004.43        |  1013.09        |  1020.26       |  1051.6         | -0.1734 |     0.3918 |           0 |           0 |         0 |
| air_temperature                          |    6456 |     6.52034     |     9.29862     |  -15.0238      |    -0.77        |     4.495       |    15.1678     |    28.2978      |  0.1192 |    -1.0628 |           0 |           0 |         0 |
| relative_humidity                        |    6456 |    84.6073      |    12.0602      |   40.3222      |    79.2667      |    88.4333      |    93.3333     |   100           | -1.3215 |     1.2429 |           0 |           0 |         0 |
| wind_direction                           |    6456 |   198.822       |    60.8053      |   37.3452      |   152.211       |   205.103       |   244.425      |   345.583       | -0.2603 |    -0.5992 |           0 |           0 |         0 |
| Down_Cap                                 |    6456 |    16.9905      |    54.8454      |    0           |     9.15        |    12.62        |    19          |  1837.22        | 31.4258 |  1014.84   |           0 |           0 |        40 |
| Up_Cap                                   |    6456 |    19.7825      |    20.422       |    0           |    10.14        |    14.35        |    20          |   286.65        |  4.9273 |    34.8436 |           0 |           0 |        40 |
| is_public_holiday                        |    6456 |     0.0334572   |     0.179841    |    0           |     0           |     0           |     0          |     1           |  5.19   |    24.9437 |           0 |           0 |      6240 |
| electricity_consumption                  |    6456 | 24552.4         | 11310.6         | 8446.73        | 11453.3         | 28922.1         | 33844.2        | 46567.5         | -0.1749 |    -1.6009 |           0 |           0 |         0 |
| electricity_consumption_Finnish_networks |    6456 |     5.73488e+06 |     1.39742e+06 |    3.00898e+06 |     4.60435e+06 |     5.73308e+06 |     6.9112e+06 |     9.10016e+06 |  0.0522 |    -1.0868 |           0 |           0 |         0 |
| electricity_consumption_forecast         |    6456 | 24917.9         | 11552.4         | 8503.85        | 11400.1         | 29725.8         | 34335.1        | 44358.7         | -0.2187 |    -1.6456 |           0 |           0 |         0 |

## Outlier summary (IQR method)

|                                          |   n_outliers |   pct_outliers |
|:-----------------------------------------|-------------:|---------------:|
| precipitation_amount                     |         1134 |       17.5651  |
| Up_Cap                                   |          618 |        9.57249 |
| sp                                       |          564 |        8.73606 |
| Down_Cap                                 |          357 |        5.52974 |
| relative_humidity                        |          321 |        4.97212 |
| is_public_holiday                        |          216 |        3.34572 |
| Down                                     |          191 |        2.95849 |
| pressure                                 |          142 |        2.1995  |
| Up                                       |          119 |        1.84325 |
| wind_speed                               |          101 |        1.56444 |
| cloud_amount                             |            0 |        0       |
| air_temperature                          |            0 |        0       |
| wind_direction                           |            0 |        0       |
| electricity_consumption                  |            0 |        0       |
| electricity_consumption_Finnish_networks |            0 |        0       |
| electricity_consumption_forecast         |            0 |        0       |

## Correlation (top absolute correlations)

| var1                                     | var2                                     |   corr_abs |
|:-----------------------------------------|:-----------------------------------------|-----------:|
| electricity_consumption_forecast         | electricity_consumption                  |   0.980061 |
| electricity_consumption_Finnish_networks | air_temperature                          |   0.838028 |
| sp                                       | Up                                       |   0.703325 |
| air_temperature                          | electricity_consumption                  |   0.641979 |
| air_temperature                          | electricity_consumption_forecast         |   0.62581  |
| electricity_consumption_Finnish_networks | electricity_consumption                  |   0.585945 |
| electricity_consumption_Finnish_networks | Down                                     |   0.581113 |
| electricity_consumption_forecast         | electricity_consumption_Finnish_networks |   0.57225  |
| air_temperature                          | Down                                     |   0.566335 |
| Down                                     | sp                                       |   0.564969 |
| Up_Cap                                   | sp                                       |   0.531267 |
| cloud_amount                             | relative_humidity                        |   0.525532 |
| Up                                       | Down                                     |   0.4874   |
| air_temperature                          | relative_humidity                        |   0.474923 |
| Up_Cap                                   | Up                                       |   0.380067 |
| air_temperature                          | cloud_amount                             |   0.366799 |
| Down                                     | electricity_consumption                  |   0.360284 |
| electricity_consumption_Finnish_networks | cloud_amount                             |   0.358936 |
| sp                                       | wind_speed                               |   0.349636 |
| Down                                     | electricity_consumption_forecast         |   0.342663 |


## Plots

- Saved histograms for numeric columns to `/kaggle/working/plots`

- Saved time-series sample plots to `/kaggle/working/plots`

- Saved correlation heatmap to `/kaggle/working/plots` (if generated)
