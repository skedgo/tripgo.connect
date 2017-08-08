# tripgo.connect
To connect any transport service provider (e.g. dockless bike share) to a unified API

## How to start

### Connect to this API

Visit https://tripgo.connect/tsp/ for a list of transport service providers, and documentation on how to connect to this service.

### Connect another transport service provider

1. Fork the repository
1. Clone your fork
1. Copy the stub for your preferred language (e.g., stubs/python) to a new directory for the transport service provider (e.g., tsp/trawesome)
1. Fill in the copy
1. Commit the changes
1. Push the changes
1. Submit a pull request

### Enhance an existing connection

1. Fork the repository
1. Clone your fork
1. Locate the transport service provider's code (e.g., tsp/trawsome)
1. Edit the code
1. Commit the changes
1. Push the changes
1. Submit a pull request

### Run your own connectors

1. Install [Docker](https://www.docker.com/)
1. Locate the transport service provider you want to run (e.g., trawsome)
1. [Run](https://docs.docker.com/engine/reference/run/) the image in a container (e.g., `docker run --publish 80:8080 --detach tripgo.connect/trawsome`)

## Where to see my contribution

* TripGo [Android](https://play.google.com/store/apps/details?id=com.buzzhives.android.tripplanner), [iOS](https://itunes.apple.com/app/tripgo/id533630842), [Web](https://tripgo.com/)
* [Edit this file](https://github.com/skedgo/tripgo.connect/edit/master/README.md) and make a pull request to add your end-user product

## How my contribution is used

We will host one instance of this project at https://tripgo.connect/tsp/ .  Others may also run their own instances as ours will have quotas and be rate-limited.

We consume this API in our TripGo app and we and others may also consume your contribution in their transport apps.
