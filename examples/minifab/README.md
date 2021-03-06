# Simple minifab example

This example uses [minifab](https://github.com/litong01/minifabric).

This example targets Hyperledger 2.2.

## Start the example

Make sure Docker and docker-compose are installed.

```bash
$> ./start.sh
```

# Access Splunk

Splunk runs as part of the deployment on your machine, and is available at `https://localhost:8000`.

You can log in with `admin/changeme`. Splunk installs the Hyperledger Fabric application, from which you can explore your setup.

## Stopping the sample

When done, make sure to stop the network. The following script will remove all containers, their volumes and images.

```bash
$> ./stop.sh
```
