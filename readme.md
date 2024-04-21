
# Food Waste around the World 🌍

This repository provides information about food waste statistics from various countries around the world. It includes data on total food waste per capita per year, household waste, retail waste, and food service waste. Additionally, it offers endpoints for retrieving specific country-wise or fruit-wise food waste data.

## Data Table

- `country`: Country name
- `combined_figures_(kg/capita/year)`: Total food waste per kg per person per year
- `household_estimate_(kg/capita/year)`: Household waste per kg per household per year
- `retail_estimate_(kg/capita/year)`: Retail waste per kg per retail per year
- `food_service_estimate_(kg/capita/year)`: Food service waste per kg per service per year
- `Region`: Region based on each country

## Endpoints

- **All Country Food Waste**: 
  - Endpoint: `/foodwastes`
  - Description: Retrieves data for food waste from all countries around the world.

- **Country-wise Food Waste**:
  - Endpoint: `/foodwastes/{country}`
  - Description: Retrieves food waste data for a specific country. Replace `{country}` with the desired country name.

- **Fruit-wise Food Waste**:
  - Endpoint: `/foodwastes/{fruit}`
  - Description: Retrieves food waste data for a specific fruit. Replace `{fruit}` with the desired fruit emoji. Available fruits: 🍐🍉🍈🍇🍍🥭🍌

## Example Usage

- Retrieve data for all countries:
  ```bash
  curl https://api.example.com/foodwastes
Retrieve data for France:


- Retrieve data for France:
  ```bash
  curl https://api.example.com/foodwastes/france

- Retrieve data for Pear:
  ```bash
  curl https://api.example.com/foodwastes/🍐

  
Feel free to explore and utilize the provided endpoints to access food waste statistics according to your needs. Let's work towards reducing food waste worldwide! 🌍🙃
