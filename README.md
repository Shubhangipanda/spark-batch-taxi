
# NYC Taxi Data Analysis with Spark

## NYC Yellow Taxi Dataset - Column Descriptions

| Column | Description |
|--------|-------------|
| **VendorID** | Taxi company (1 = Creative Mobile, 2 = VeriFone). |
| **tpep_pickup_datetime** | Date & time when the trip started. |
| **tpep_dropoff_datetime** | Date & time when the trip ended. |
| **passenger_count** | Number of passengers in the cab. |
| **trip_distance** | Distance of the trip in miles. |
| **RatecodeID** | Pricing category (1 = standard, 2 = JFK flat rate, etc.). |
| **store_and_fwd_flag** | “Y” if trip record was stored & sent later, “N” otherwise. |
| **PULocationID** | Pickup location (Taxi Zone ID). |
| **DOLocationID** | Drop-off location (Taxi Zone ID). |
| **payment_type** | Payment method (1 = Credit card, 2 = Cash, etc.). |
| **fare_amount** | Base fare charged by distance/time. |
| **extra** | Extra charges (e.g., late-night, rush hour). |
| **mta_tax** | $0.50 tax automatically added. |
| **tip_amount** | Tip paid by passenger. |
| **tolls_amount** | Toll charges during the trip. |
| **improvement_surcharge** | $0.30 per trip improvement fee. |
| **total_amount** | Total cost = fare + extras + tax + tip + tolls. |
| **congestion_surcharge** | Congestion fee for trips in Manhattan zones. |

