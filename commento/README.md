# commento

docker-compose config for the [Commento](https://commento.io) self-hosted comments platform.

## Usage instructions

- Copy the `.env.sample` file to `.env` and replace the placeholder data with your production config.
- Run `docker-compose up` to allow the database to be created and populated, and log into the web interface to verify that everything works fine.
- Press Ctrl + C to stop the containers safely, then `docker-compose up -d` to run them in detached mode.
