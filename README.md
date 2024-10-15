# IBM Environmental Intelligence

This repository contains sample applications of [IBM Environmental Intelligence](https://www.ibm.com/products/environmental-intelligence) - a platform designed to empower data scientists and application developers with environmental data and insights. 

Sign up for a [free preview](https://www.ibm.com/account/reg/us-en/signup?formid=urx-52894) to receive API credentials for working with the samples below. 

Consider taking our free training course on [Environmental Intelligence: Geospatial APIs for Data Scientists and Application Developers](https://www.ibm.com/training/course/environmental-intelligence-geospatial-apis-for-data-scientists-and-application-developers-DL25641G) for an introduction to IBM's Environmental Intelligence API and industry use cases.

### General Notes

If you like to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md)
first. A list of maintainers is recorded in [MAINTAINERS.md](MAINTAINERS.md).

## Geospatial APIs
For documentation and tutorials regarding how to use the `ibmpairs` SDK for Geospatial APIs, please consult the [official documentation](https://ibm.github.io/ibmpairs/).

Refer to the samples below for various industry use cases of Geospatial APIs.

Example | Description                                                                                                                                                                                                                                                                            | Industry
--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------
[Normalized Difference Vegetation Index (NDVI)](geospatial_analytics/v3_apis/samples/industry_use_cases/agriculture_ndvi/normalized_difference_vegetation_index_analysis.ipynb) | Normalized Difference Vegetation Index (NDVI) is used to quantify vegetation greenness and is useful in understanding vegetation density and assessing changes in plant health.                                                                                                        | Agriculture
[Water and Moisture Detection](geospatial_analytics/v3_apis/samples/industry_use_cases/agriculture_water_and_moisture_detection/water_and_moisture_detection.ipynb) | Normalized Difference Moisture Index (NDMI) and Modified Normalized Difference Water Index (mNDWI) provides a relative indication of the wetness or dryness of an area, helping to identify potential water stress or drought conditions or combustibility levels in fire-prone areas. | Agriculture, Disaster Events
[Sea Rise Risk Prediction](geospatial_analytics/v3_apis/samples/industry_use_cases/climate_change_tidal_surge/sea_rise_risk_prediction.ipynb) | Geospatial APIs can help determine the possible regions that come under the threat of rise in sea levels                                                                                                                                                                               | Climate Change, Disaster Events
[TWC Seasonal Forecast Weather Prediction](geospatial_analytics/v3_apis/samples/industry_use_cases/weather_forecast/twc_spfp_weather_prediction.ipynb) | TWC Seasonal Forecast (SPFP) provides essential insights into anticipated weather patterns over the coming months, aiding industries in strategic planning and decision-making                                                                                                         | Climate Change, Weather Forecast

## Geospatial APIs Above Ground Biomass (AGB)

To know the basics of Geospatial APIs Above Ground Biomass (AGB) Dataset, start with the [AGB Catalogue](geospatial_analytics/v4_apis/samples/quickstart/agb_catalogue/agb_catalogue.ipynb) sample.

To get an understanding of the Geospatial APIs Above Ground Biomass (AGB) Species Agnostic usage refer to [AGB Species Agnostic](geospatial_analytics/v4_apis/samples/quickstart/agb_species_agnostic/agb_species_agnostic.ipynb) sample.

To get an understanding of the Geospatial APIs Above Ground Biomass (AGB) Species Specific usage refer to [AGB Species Specific](geospatial_analytics/v4_apis/samples/quickstart/agb_species_specific/agb_species_specific.ipynb) sample.

Refer to the samples below for various industry use cases of Geospatial APIs Above Ground Biomass (AGB)

Example | Description                                                                                                                                                            | Industry
--------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------
[Historical Difference AGB](geospatial_analytics/v4_apis/samples/industry_use_cases/disaster_events_deforestation/historical_difference_in_agb.ipynb) | Above Ground Biomass (AGB) can be used to find out how much the AGB cover has changed over the years for various use case like measuring deforestation, wildfires etc. | Disaster Events

## Historical Weather On Demand 

Refer to the samples for:

[Historical Weather On Demand - Direct API](historical_weather_on_demand/samples/quickstart/historical_weather_on_demand_direct/historical_weather_on_demand_direct.ipynb)

[Historical Weather On Demand - HDAT API](historical_weather_on_demand/samples/quickstart/historical_weather_on_demand_hdat/historical_weather_on_demand_hdat.ipynb)


## GHG Emissions

Refer to the core samples for:

#### Scope 1

[Stationary Emission API](ghg_emissions/tutorials/scope1/stationary_emission.ipynb)

[Fugitive Emission API](ghg_emissions/tutorials/scope1/fugitive_emission.ipynb)

[Mobile Emission API](ghg_emissions/tutorials/scope1/mobile_emission.ipynb)

#### Scope 2

[Location Based Emission API](ghg_emissions/tutorials/scope2/location_based_emission.ipynb)

[Market Based Emission API](ghg_emissions/tutorials/scope2/market_based_emission.ipynb)

#### Scope 3

[Transportation and Distribution Based Emission API](ghg_emissions/tutorials/scope3/transportation_and_distribution_emission.ipynb)

Refer to the samples below for various industry use cases of Greenhouse Gas (GHG) Emissions APIs 

Example | Description                                                                                                                                                            | Scope
--------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------
[Carbon Aware Crew Scheduling](ghg_emissions/samples/scope1/sustainable_crew_scheduling/carbon_aware_crew_scheduling.ipynb) |Evaluate the vehicle's emissions based on fuel usage which can help to estimate carbon impact of different routes for crew scheduling while full-filling the work orders using GHG Mobile Emissions API. | 1
[Refrigeration Leaks Insights](ghg_emissions/samples/scope1/refrigeration_leaks_insights/refrigeration_leaks_insights.ipynb) |This use case calculates fugitive emissions for an organization operating large scale and geographically diverse refrigeration assets using Fugitive Emissions API. | 1
[Environmental Impact of Power Plants](ghg_emissions/samples/scope1/environmental_impact_of_power_plant/power_plant.ipynb) |The primary focus of this sample will be on calculating emissions for different fuel types (e.g., coal, natural gas, oil) used in Power Plants based on a given energy consumption using the GHG Stationary Emission API. | 1
[Datacenter Emissions](ghg_emissions/samples/scope2/datacenter_emission_capture/datacenter_emission_capture.ipynb) |This use case demonstrates that by understanding the datacenter emissions using  the GHG Location and Market API , datacenter operators can assess their environmental impact for reporting and identify opportunities for emissions reduction.| 2
[Freight Transport Emission](ghg_emissions/samples/scope3/freight_transport_emission_capture/freight_transport_emission_capture.ipynb) |This use case utilizes the Fuel Use and Vehicle Distance, Vehicle Distance, and Weight Distance methods to showcase the GHG Transportation and Distribution API used effectively for different data availablity scenarios.| 3