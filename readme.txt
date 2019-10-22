# Weather Data Integration

## Data Source

https://www.accuweather.com/

## Information we can get

- [ ] precipitation
- [ ] snow
- [ ] maxTemperature
- [ ] minTemperature
- [ ] weather summary # e.g. 'Mostly cloudy, a shower'

### Data Scope

- all data in 2019
- influding 900+ stores in Australia
- Data before 2019-08-28 is historical data, after that is forecasting data.

## How we get

Use Python Scrapy to build web crawler.

## What else has been done

We use store location to find the nearest weather observation station. Therefore, we can tag weather data to this store.

## Limitations

- Not cover all Australian stores yet. But we are keeping crawling the missing ones.
- For historical data, we dont have precipitation, snow and weather summary data.
- The forecasting period is around 3 months.