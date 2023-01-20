# Scaling NodeJS with Docker cluster mode

This project shows how to scale a NodeJS application with Docker Compose and use multiple CPU cores. It's similar to cluster mode in PM2, but with a few fundemantal differences.

## Getting started

1. Clone this repository `git clone https://github.com/imonirulislam/nodejs-docker-cluster.git && cd nodejs-docker-cluster`

2. Start the application stack scaled to four app instances `docker-compose up -d --scale app=4`

3. Visit `http://localhost` in your browser

4. Hit refresh and you will see sequential responses from each application instance