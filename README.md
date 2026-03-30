# hourly--prices--support
# Hourly Prices - Support

**Hourly Prices** is a real-time electricity price tracker for ComEd Hourly Pricing customers in Northern Illinois.

## Contact & Support

For questions, bug reports, or feature requests, please email:

**bluetomis@icloud.com**

We typically respond within 24-48 hours.

## Frequently Asked Questions

### What is ComEd Hourly Pricing?
ComEd Hourly Pricing is a program for residential customers in Northern Illinois where you pay the real-time market price for electricity instead of a flat rate. Prices change every 5 minutes based on supply and demand. Learn more at [hourlypricing.comed.com](https://hourlypricing.comed.com).

### Where does the price data come from?
All pricing data comes directly from the official ComEd Hourly Pricing API. The app fetches the latest 5-minute price and current hour average every 5 minutes, matching the ComEd update frequency.

### How do widgets work?
Hourly Prices offers widgets for both iPhone and Apple Watch:
- **Current Price** — shows the latest 5-minute electricity price
- **Average Price** — shows the current hour average price

Widgets update every 5 minutes. To add a widget, long-press your home screen (iPhone) or watch face (Apple Watch) and select Hourly Prices.

### How does HomeKit automation work?
You can connect smart home devices through HomeKit and set price-based rules:
- **Turn ON** devices when the price drops below your threshold (great for EV chargers, pool pumps)
- **Turn OFF** devices when the price rises above your threshold (save during peak hours)

You can set independent rules for both the 5-minute price and the hour average.

### What do negative prices mean?
When electricity demand is very low (typically overnight or on mild days), prices can go negative. This means the grid is effectively paying you to use electricity. It's the best time to run heavy appliances, charge EVs, or do laundry.

### What are the price tiers?
| Tier | Price Range | Meaning |
|------|------------|---------|
| Negative | Below 0¢ | Grid is paying you |
| Very Low | 0 - 1¢ | Great time to use power |
| Low | 1 - 3¢ | Good time to use power |
| Moderate | 3 - 6¢ | Normal usage |
| High | 6 - 10¢ | Consider reducing usage |
| Very High | 10 - 20¢ | Avoid heavy appliances |
| Spike | Above 20¢ | Delay all heavy loads |

## Privacy Policy

Hourly Prices does **not** collect, store, or transmit any personal data. All pricing data is fetched directly from the public ComEd Hourly Pricing API. HomeKit device control happens entirely on your local network through Apple's HomeKit framework. No analytics, no tracking, no accounts required.

## Requirements

- iPhone running iOS 17.0 or later
- Apple Watch running watchOS 10.0 or later (for watch complications)
- ComEd Hourly Pricing enrollment (for relevant pricing data)

## Disclaimer

Hourly Prices is not affiliated with, endorsed by, or sponsored by Commonwealth Edison (ComEd) or Exelon Corporation. ComEd is a registered trademark of Commonwealth Edison Company. Pricing data is provided by the public ComEd Hourly Pricing API and is displayed as-is. The developer is not responsible for data accuracy or any financial decisions made based on the information displayed in the app.
