## Cafe Sales Data Cleaning

This project demonstrates real-world data cleaning using Pandas.

### Key Steps
- Fixed invalid values (`ERROR`, `UNKNOWN`)
- Recomputed `Total Spent` using Quantity × Price
- Inferred missing Items via unique Price → Item mapping
- Filled categorical NaNs using statistical mode
- Ensured schema cleanliness (`index=False`)

### Tech
- Python
- Pandas
