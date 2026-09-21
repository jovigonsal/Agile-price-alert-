# Agile Price Alert — iPhone/iPad PWA prototype

This is a Home Screen web-app prototype for iPhone/iPad. It reads public Octopus Agile price data, shows VAT-inclusive prices, refreshes every 5 minutes while open, and classifies prices as:

- <=5p: Very cheap
- <=10p: Cheap
- <=15p: Reasonable
- >30p: Expensive
- >40p: Very expensive — limit use

## Important
For reliable background push notifications when the app is closed, this frontend needs to be paired with a small HTTPS push backend/service worker. iOS/iPadOS supports Web Push for Home Screen web apps.

The current prototype intentionally does not include any secrets or Octopus account credentials.
