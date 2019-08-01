# Google Cloud PubSub Emulator Docker
This is the Docker image for the [Google Cloud PubSub Emulator](https://cloud.google.com/sdk/gcloud/reference/beta/emulators/pubsub/). It is intended to be used as a service on development environments (it SHOULD NOT be used in production environments).

## Usage
To use this image, pull from [Docker Hub](https://hub.docker.com/r/neowaylabs/gcloud-pubsub-emulator/), run the following command:

```
docker pull neowaylabs/gcloud-pubsub-emulator
```

to run it you can use

    docker run --rm -p "8085:8085" neowaylabs/gcloud-pubsub-emulator

## Configuration

> Notice the usage of the `PUBSUB_EMULATOR_HOST` to let the pubsub client know about the emulator.