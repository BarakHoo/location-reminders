# Location Reminders

A static web app for creating GPS/location-based reminders.

**Live demo:** https://munkys.dev/gps-reminder

> Requires geolocation access; served over HTTPS.

## Run locally
```bash
docker build -t location-reminders .
docker run --rm -p 8080:80 location-reminders
```

Then open http://localhost:8080

## Deployment
Deployed as a lightweight Nginx container behind Caddy on munkys.dev under `/gps-reminder`.
