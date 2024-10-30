# CS Club Attendance App Deployment

## Deployment steps for the attendance app

Requirements: Docker, Docker Compose

1. Clone this repo or download the compose file: [docker-compose.yml](/docker-compose.yml)
2. Create a `.env` file and set it up according to [.env.example](/.env.example)
3. Start everything using `docker compose -d`

### Managing a Deployment
**Promoting a user:** Users can either be promoted to service admin through the Users tab of the UI, or with the [promote](/promote) script (`./promote <email>`)
