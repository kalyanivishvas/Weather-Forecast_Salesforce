Phase 8: Data Management & Deployment

🎯 Objective

Import sample data and deploy project to scratch org or sandbox.

📝 Steps

1. Optional CSV: data/Weather_Cities.csv → list of cities for testing.


2. Use Data Loader / CLI to upsert test data.


3. Push source:



sfdx force:source:push -u WeatherDev

4. Validate deployed components in Org.
