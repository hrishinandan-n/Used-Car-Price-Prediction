# Used-Car-Price-Prediction

## Problem Statement

Accurately pricing used cars is a common challenge in the automobile market.  
This project aims to build regression models that can estimate the **market value of a used car** using historical data, helping buyers and sellers make informed decisions.

## Dataset Overview

- Each row represents a single used car listing.
- The dataset contains vehicle specifications, usage history, and condition-related attributes.
- Both numerical and categorical features are present.
- The goal is to predict the selling price of a used car based on these features.

### Features

- `make_year`: Year the vehicle was manufactured.
- `mileage_kmpl`: Fuel efficiency measured in kilometers per liter.
- `engine_cc`: Engine displacement in cubic centimeters.
- `fuel_type`: Type of fuel used by the vehicle.
- `owner_count`: Number of previous owners.
- `brand`: Manufacturer of the car.
- `transmission`: Transmission type (Manual/Automatic).
- `color`: Exterior color of the vehicle.
- `service_history`: Indicates whether the car has a full or partial service history.
- `accidents_reported`: Number of accidents reported for the vehicle.
- `insurance_valid`: Indicates whether the vehicle has valid insurance.

**Target**
- `price_usd`: Selling price of the used car (continuous variable).
